---
inclusion: manual
contextKey: validation
---

# Mermaid Validation Script and Procedures

## Automated Validation Commands

### Check All Mermaid Files for Syntax Issues
```bash
# Check for common syntax problems
echo "=== Checking for Direction Statement Issues ==="
grep -n "^direction" Mermaid01/*.md

echo "=== Checking for Incomplete Brackets ==="
grep -n "\[[^]]*$" Mermaid01/*.md

echo "=== Checking for Mixed Direction and Node Declarations ==="
grep -n "direction.*\[" Mermaid01/*.md

echo "=== Checking for Double Closing Brackets ==="
grep -n "\]\]" Mermaid01/*.md

echo "=== Checking for Invalid Arrow Types ==="
grep -n " -> \| => " Mermaid01/*.md

echo "=== Checking for Unquoted Subgraph Titles ==="
grep -n "subgraph [^\"']" Mermaid01/*.md
```

### Validate Each File Structure
```bash
# Check each file for proper Mermaid block structure
for file in Mermaid01/*.md; do
    echo "Validating $file"
    
    # Check if file has proper mermaid code blocks
    if ! grep -q "```mermaid" "$file"; then
        echo "  ❌ No mermaid code block found"
        continue
    fi
    
    # Extract mermaid content and check basic syntax
    sed -n '/```mermaid/,/```/p' "$file" | sed '1d;$d' > /tmp/mermaid_temp.txt
    
    # Check for graph declaration
    if ! grep -q "^graph" /tmp/mermaid_temp.txt; then
        echo "  ❌ No graph declaration found"
    else
        echo "  ✅ Graph declaration found"
    fi
    
    # Check for proper subgraph syntax
    if grep -q "subgraph" /tmp/mermaid_temp.txt; then
        if grep -q 'subgraph "' /tmp/mermaid_temp.txt; then
            echo "  ✅ Proper subgraph syntax"
        else
            echo "  ⚠️  Check subgraph title quotes"
        fi
    fi
    
    # Check for class definitions
    if grep -q "classDef" /tmp/mermaid_temp.txt; then
        echo "  ✅ Class definitions found"
    else
        echo "  ⚠️  No class definitions (optional)"
    fi
    
    echo ""
done

rm -f /tmp/mermaid_temp.txt
```

## Manual Validation Checklist

For each Mermaid diagram file, verify:

### 1. File Structure
- [ ] File starts with proper markdown header
- [ ] Contains `## Mermaid Diagram` section
- [ ] Has properly formatted code block: ` ```mermaid`
- [ ] Code block is properly closed: ` ``` `

### 2. Mermaid Syntax
- [ ] Starts with `graph TD` or `graph TB`
- [ ] All subgraphs have quoted titles: `subgraph "Title"`
- [ ] Direction statements are inside subgraphs
- [ ] All node IDs are alphanumeric (A1, B2, C3)
- [ ] All node labels have proper brackets: `[Label]`
- [ ] Connections use proper arrows: `-->`
- [ ] Class definitions come after graph structure
- [ ] Class applications reference existing nodes

### 3. Content Quality
- [ ] Layout flows top-to-bottom
- [ ] Subgraphs are logically organized
- [ ] Node labels are descriptive and accurate
- [ ] Colors and styling enhance readability
- [ ] No crossing connections where avoidable

## Common Fix Patterns

### Fix 1: Direction Statement Issues
```mermaid
# ❌ WRONG
direction TD E1[General]

# ✅ CORRECT
subgraph "Section"
    direction TD
    E1[General]
end
```

### Fix 2: Incomplete Node Labels
```mermaid
# ❌ WRONG
E1[General Provisions  # Missing closing bracket

# ✅ CORRECT
E1[General Provisions]
```

### Fix 3: Unquoted Subgraph Titles
```mermaid
# ❌ WRONG
subgraph Part III: Fundamental Rights

# ✅ CORRECT
subgraph "Part III: Fundamental Rights"
```

### Fix 4: Wrong Arrow Types
```mermaid
# ❌ WRONG
A1 -> A2
A2 => A3

# ✅ CORRECT
A1 --> A2
A2 --> A3
```

## Batch Correction Script

```bash
#!/bin/bash
# Batch fix common Mermaid syntax issues

echo "Starting batch correction of Mermaid files..."

for file in Mermaid01/*.md; do
    echo "Processing $file"
    
    # Create backup
    cp "$file" "$file.backup"
    
    # Fix common issues (be careful with these - test first!)
    # sed -i 's/subgraph \([^"]\)/subgraph "\1/g' "$file"  # Add quotes to subgraph titles
    # sed -i 's/ -> / --> /g' "$file"                      # Fix arrow types
    # sed -i 's/ => / --> /g' "$file"                      # Fix arrow types
    
    echo "  Backup created: $file.backup"
done

echo "Batch correction complete. Please validate all files manually."
```

## Testing Procedure

### 1. Online Validation
For each diagram:
1. Copy the Mermaid code (between ` ```mermaid` and ` ``` `)
2. Paste into https://mermaid.live
3. Verify it renders without errors
4. Check layout is readable and properly formatted

### 2. Local Testing
```bash
# If you have mermaid-cli installed
mmdc -i input.mmd -o output.png

# Or use node.js validation
node -e "
const mermaid = require('mermaid');
const fs = require('fs');
const content = fs.readFileSync('diagram.mmd', 'utf8');
try {
    mermaid.parse(content);
    console.log('✅ Valid syntax');
} catch (e) {
    console.log('❌ Syntax error:', e.message);
}
"
```

## Error Recovery

### If Validation Fails
1. **Identify**: Use grep commands to find specific issues
2. **Isolate**: Comment out problematic sections with `%%`
3. **Fix**: Apply corrections from the syntax guide
4. **Test**: Validate each section individually
5. **Restore**: Uncomment fixed sections

### If Multiple Files Affected
1. **Backup**: Create backups of all files first
2. **Pattern**: Identify common error patterns
3. **Batch**: Apply same fix to similar issues
4. **Validate**: Test each file after correction

## Quality Metrics

Track these metrics for diagram quality:
- **Syntax Errors**: 0 errors in all files
- **Rendering Success**: 100% of diagrams render correctly
- **Layout Quality**: All diagrams are readable and well-formatted
- **Consistency**: All files follow the same syntax patterns
- **Documentation**: All diagrams have proper analysis notes

## Maintenance Schedule

### Daily
- Check any newly created diagrams
- Validate syntax before committing changes

### Weekly
- Run full validation script on all files
- Check for any rendering issues
- Update syntax guide if new patterns emerge

### Monthly
- Review and update validation procedures
- Check for new Mermaid syntax features
- Optimize diagram layouts and styling