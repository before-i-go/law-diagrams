# Standard Operating Procedure v1.0
## Constitution of India Analysis and Mermaid Diagram Creation

### Purpose
This SOP outlines the systematic approach for analyzing the Constitution of India text file and creating Mermaid diagrams to visualize constitutional concepts, structures, and processes.

### Scope
Analysis of `RAWDATA/EnglishCOI202407_extracted_text.txt` (20,115 lines) through structured task breakdown and selective diagram creation.

---

## 1. Task Structure and Breakdown

### 1.1 File Segmentation
- **Source File:** `/home/amuldotexe/Desktop/before-I-go/law-diagrams/RAWDATA/EnglishCOI202407_extracted_text.txt`
- **Total Lines:** 20,115
- **Chunk Size:** 100 lines per task
- **Total Tasks:** 202 tasks (201 full chunks + 1 partial chunk)

### 1.2 Task Numbering System
- Tasks numbered sequentially: 001-202
- Zero-padded three-digit format for consistent sorting
- Each task covers exactly 100 lines (except final task: 15 lines)

---

## 2. Reading and Analysis Process

### 2.1 Sequential Reading Protocol
1. **Read Assigned Lines:** Extract exactly 100 lines for each task
2. **Content Analysis:** Identify key constitutional concepts, structures, and processes
3. **Diagram Assessment:** Evaluate whether content warrants Mermaid diagram creation
4. **Documentation:** Record findings and decisions in task tracking

### 2.2 Line Range Calculation
- **Task N:** Lines `((N-1) × 100) + 1` to `N × 100`
- **Example:** Task 025 = Lines 2401-2500
- **Final Task 202:** Lines 20101-20115

---

## 3. Mermaid Diagram Creation Criteria

### 3.1 Content Types Requiring Diagrams
Create diagrams when encountering:

**Structural Elements:**
- Constitutional hierarchy and organization
- Government branches and their relationships
- Institutional frameworks
- Federal-state power distribution

**Process Elements:**
- Legislative procedures and workflows
- Judicial processes and appeals structure
- Amendment procedures
- Electoral processes

**Conceptual Elements:**
- Rights and duties frameworks
- Emergency provisions structure
- Constitutional principles relationships
- Checks and balances systems

### 3.2 Diagram Types and Applications

| Content Type | Recommended Diagram | Use Case |
|--------------|-------------------|----------|
| Government Structure | Organizational Chart | Hierarchy visualization |
| Legislative Process | Flowchart | Step-by-step procedures |
| Judicial Appeals | Sequence Diagram | Court progression |
| Rights Framework | Mind Map | Interconnected concepts |
| Amendment Process | Flowchart | Procedural steps |
| Federal Relations | Network Diagram | Inter-governmental relationships |

---

## 4. File Management and Naming

### 4.1 Directory Structure
```
Mermaid01/
├── M01_[topic]_[task_number].md
├── constitutional_structure.md (existing)
└── [additional diagrams as created]
```

### 4.2 File Naming Convention
**Format:** `M[sequential_number]_[topic].md`

**Examples:**
- `M01_constitutional_structure.md`
- `M02_fundamental_rights_structure.md`
- `M03_directive_principles_duties.md`
- `M04_executive_parliament_structure.md`
- `M05_legislative_procedures.md`

**Note:** Sequential numbering (M01, M02, M03...) represents the order of diagram creation, not task numbers.

### 4.3 Topic Naming Guidelines
- Use lowercase with underscores
- Keep names concise but descriptive
- Avoid special characters and spaces
- Maximum 20 characters for topic portion

---

## 5. Quality Control and Standards

### 5.1 Diagram Quality Requirements
- **Clarity:** Diagrams must be easily readable and understandable
- **Accuracy:** Content must accurately reflect constitutional provisions
- **Completeness:** Include all relevant elements for the topic
- **Consistency:** Follow established visual and naming conventions

### 5.2 Content Validation
- Cross-reference with original constitutional text
- Verify accuracy of relationships and hierarchies
- Ensure compliance with current amendments (up to 106th Amendment Act, 2023)

---

## 6. Progress Tracking and Documentation

### 6.1 Task Completion Tracking
- Use checkbox format in `MermaidTasks.md`
- Mark completed tasks with `[x]`
- Update progress counters regularly
- Document any skipped tasks with reasoning

### 6.2 Metrics to Track
- **Tasks Completed:** X/202
- **Diagrams Created:** Count of new diagram files
- **Coverage Areas:** Major constitutional sections addressed
- **Quality Issues:** Any corrections or revisions needed

---

## 7. Workflow Execution Steps

### 7.1 For Each Task
1. **Prepare:** Identify task number and line range
2. **Read:** Extract specified lines from source file
3. **Analyze:** Review content for diagram-worthy concepts
4. **Decide:** Determine if diagram creation is warranted
5. **Create:** If yes, develop appropriate Mermaid diagram
6. **Save:** Store diagram in `Mermaid01/` with proper naming
7. **Track:** Update task completion status
8. **Document:** Record any notable findings or decisions

### 7.2 Decision Matrix for Diagram Creation
- **High Priority:** Structural relationships, key processes, complex hierarchies
- **Medium Priority:** Supporting concepts, detailed procedures, specific provisions
- **Low Priority:** Repetitive content, minor details, administrative text

---

## 8. Review and Maintenance

### 8.1 Periodic Review Schedule
- **Daily:** Review completed tasks and diagram quality
- **Weekly:** Assess overall progress and adjust approach if needed
- **Upon Completion:** Comprehensive review of all created diagrams

### 8.2 Continuous Improvement
- Document lessons learned during execution
- Refine diagram creation criteria based on experience
- Update SOP as needed for future iterations

---

## 9. Deliverables

### 9.1 Primary Outputs
- **Task Tracking File:** `MermaidTasks.md` (with completion status)
- **Mermaid Diagrams:** Collection of `.md` files in `Mermaid01/` folder
- **Analysis Documentation:** Notes on constitutional structure and relationships

### 9.2 Success Criteria
- All 202 tasks completed and tracked
- Comprehensive diagram coverage of major constitutional elements
- High-quality, accurate visual representations
- Organized file structure for easy navigation and reference

---

**Document Version:** 1.0  
**Created:** As per user requirements  
**Last Updated:** Initial creation  
**Next Review:** Upon completion of first 50 tasks