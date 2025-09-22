# State Government and Legislature Structure

## Overview
This diagram visualizes the comprehensive structure of State Government and Legislature as outlined in Part VI of the Constitution of India, showing the relationships between the Governor, Council of Ministers, and the bicameral/unicameral legislature systems.

## Constitutional Significance
This section establishes the framework for state-level governance, defining the executive and legislative structures that mirror the Union government while maintaining state autonomy within the federal system.

## Key Articles Covered
- **Articles 153-167**: State Executive (Governor, Ministers, Advocate-General)
- **Articles 168-212**: State Legislature (Composition, Officers, Procedures)
- **Articles 148-151**: Comptroller and Auditor-General (oversight function)

```mermaid
graph TD
    Constitution[Constitution of India]
    Constitution --> PartVI[PART VI: THE STATES]
    
    PartVI --> StateExec[Chapter II: State Executive]
    PartVI --> StateLeg[Chapter III: State Legislature]
    
    subgraph "State Executive Structure"
        StateExec --> Governor[Governor<br/>Art 153-162]
        Governor --> CouncilMin[Council of Ministers<br/>Art 163-164]
        Governor --> AdvGen[Advocate-General<br/>Art 165]
        
        CouncilMin --> ChiefMin[Chief Minister<br/>Head of Council]
        CouncilMin --> Ministers[Other Ministers<br/>Max 15% of Assembly]
        
        ChiefMin --> Duties[Duties to Governor<br/>Art 167]
    end
    
    subgraph "State Legislature Types"
        StateLeg --> Bicameral[Bicameral States<br/>Art 168]
        StateLeg --> Unicameral[Unicameral States<br/>Art 168]
        
        Bicameral --> LegAssembly[Legislative Assembly<br/>Art 170]
        Bicameral --> LegCouncil[Legislative Council<br/>Art 171]
        
        Unicameral --> Assembly[Legislative Assembly<br/>Art 170]
    end
    
    subgraph "Legislative Assembly Structure"
        LegAssembly --> AssemblyComp[Composition<br/>60-500 members<br/>Direct election]
        AssemblyComp --> Speaker[Speaker & Deputy Speaker<br/>Art 178-181]
        AssemblyComp --> Duration[Duration: 5 years<br/>Art 172]
    end
    
    subgraph "Legislative Council Structure"
        LegCouncil --> CouncilComp[Composition<br/>Max 1/3 of Assembly<br/>Min 40 members]
        CouncilComp --> Chairman[Chairman & Deputy Chairman<br/>Art 182-185]
        CouncilComp --> Permanent[Permanent House<br/>1/3 retire every 2 years]
        
        CouncilComp --> ElectionMethod[Election Methods<br/>Art 171]
        ElectionMethod --> LocalAuth[1/3 by Local Authorities]
        ElectionMethod --> Graduates[1/12 by Graduates]
        ElectionMethod --> Teachers[1/12 by Teachers]
        ElectionMethod --> MLAs[1/3 by MLAs]
        ElectionMethod --> Nominated[Remainder Nominated]
    end
    
    subgraph "Legislative Procedures"
        StateLeg --> Sessions[Sessions & Prorogation<br/>Art 174-176]
        StateLeg --> Voting[Voting & Quorum<br/>Art 189]
        StateLeg --> Privileges[Powers & Privileges<br/>Art 194]
        StateLeg --> Disqualifications[Disqualifications<br/>Art 190-193]
    end
    
    subgraph "Oversight & Audit"
        CAG[Comptroller & Auditor-General<br/>Art 148-151]
        CAG --> StateAudit[State Accounts Audit]
        CAG --> Reports[Reports to Governor<br/>Laid before Legislature]
    end
    
    Governor --> Sessions
    CouncilMin --> LegAssembly
    StateAudit --> StateLeg
    
    classDef executive fill:#fff8e1,stroke:#f57f17,stroke-width:2px
    classDef legislative fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef oversight fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef foundation fill:#e1f5fe,stroke:#01579b,stroke-width:3px
    
    class Governor,CouncilMin,ChiefMin,Ministers,AdvGen,Duties executive
    class StateLeg,LegAssembly,LegCouncil,Assembly,Speaker,Chairman,Sessions,Voting,Privileges,Disqualifications legislative
    class CAG,StateAudit,Reports oversight
    class Constitution,PartVI foundation
```

## Constitutional Framework Analysis

### State Executive Authority
- **Governor**: Constitutional head appointed by President (Art 155)
- **Council of Ministers**: Real executive power with Chief Minister as head
- **Collective Responsibility**: Ministers collectively responsible to Legislative Assembly
- **Size Limitation**: Maximum 15% of Assembly strength, minimum 12 ministers

### Legislative Structure Variations
- **Bicameral States**: Currently 6 states with both Assembly and Council
- **Unicameral States**: Majority of states with only Legislative Assembly
- **Flexibility**: Parliament can create/abolish Legislative Councils on state request

### Democratic Accountability
- **Assembly**: Directly elected, 5-year term, subject to dissolution
- **Council**: Indirectly elected/nominated, permanent house with staggered retirement
- **Oversight**: CAG audit reports ensure financial accountability

### Federal Integration
- **Governor's Role**: Link between Union and State governments
- **Constitutional Compliance**: State actions subject to constitutional limitations
- **Audit Oversight**: Central CAG ensures uniform audit standards

This structure ensures democratic governance at state level while maintaining federal unity and constitutional supremacy.