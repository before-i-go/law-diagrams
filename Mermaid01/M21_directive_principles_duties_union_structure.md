# Directive Principles, Fundamental Duties, and Union Structure

## Overview
This diagram visualizes the relationship between Part IV (Directive Principles of State Policy), Part IVA (Fundamental Duties), and Part V (The Union) of the Constitution of India, showing how state obligations, citizen duties, and governmental structures interconnect.

## Constitutional Significance
- **Part IV (Articles 36-51)**: Non-enforceable principles fundamental to governance
- **Part IVA (Article 51A)**: Fundamental duties of every citizen
- **Part V (Articles 52-98)**: Structure and powers of the Union Government

## Key Articles Covered
- Articles 36-51: Directive Principles of State Policy
- Article 51A: Fundamental Duties
- Articles 52-78: Union Executive (President, Vice-President, Council of Ministers)
- Articles 79-98: Parliament (Council of States, House of the People)

```mermaid
graph TD
    Constitution[Constitution of India]
    Constitution --> PartIV[PART IV: Directive Principles<br/>of State Policy]
    Constitution --> PartIVA[PART IVA: Fundamental Duties]
    Constitution --> PartV[PART V: The Union]
    
    subgraph "Directive Principles (Art 36-51)"
        PartIV --> DP1[Social Order & Welfare<br/>Art 38-39]
        PartIV --> DP2[Economic Justice<br/>Art 39A, 43-43A]
        PartIV --> DP3[Social Justice<br/>Art 46, 47]
        PartIV --> DP4[Cultural & Environmental<br/>Art 48A, 49]
        PartIV --> DP5[International Relations<br/>Art 51]
        DP1 --> StatePolicy[State Policy Direction]
        DP2 --> StatePolicy
        DP3 --> StatePolicy
        DP4 --> StatePolicy
        DP5 --> StatePolicy
    end
    
    subgraph "Fundamental Duties (Art 51A)"
        PartIVA --> FD1[Constitutional Respect<br/>Art 51A(a)]
        PartIVA --> FD2[National Unity<br/>Art 51A(c,e)]
        PartIVA --> FD3[Cultural Heritage<br/>Art 51A(f)]
        PartIVA --> FD4[Environmental Protection<br/>Art 51A(g)]
        PartIVA --> FD5[Scientific Temper<br/>Art 51A(h)]
        FD1 --> CitizenDuties[Citizen Obligations]
        FD2 --> CitizenDuties
        FD3 --> CitizenDuties
        FD4 --> CitizenDuties
        FD5 --> CitizenDuties
    end
    
    subgraph "Union Executive (Art 52-78)"
        PartV --> Executive[Chapter I: The Executive]
        Executive --> President[President<br/>Art 52-73]
        Executive --> VicePresident[Vice-President<br/>Art 63-71]
        Executive --> CouncilMinisters[Council of Ministers<br/>Art 74-75]
        Executive --> AttorneyGeneral[Attorney-General<br/>Art 76]
        
        President --> PresidentialPowers[Executive Powers<br/>Pardons, Commands]
        VicePresident --> ChairmanRS[Chairman of<br/>Council of States]
        CouncilMinisters --> PrimeMinister[Prime Minister]
        CouncilMinisters --> Ministers[Other Ministers]
    end
    
    subgraph "Parliament (Art 79-98)"
        PartV --> Parliament[Chapter II: Parliament]
        Parliament --> CouncilStates[Council of States<br/>Art 80]
        Parliament --> HousePeople[House of the People<br/>Art 81]
        
        CouncilStates --> RSComposition[238 Representatives<br/>12 Nominated]
        HousePeople --> LSComposition[530 Members<br/>20 UT Representatives]
        
        CouncilStates --> RSChairman[Chairman & Deputy<br/>Art 89-92]
        HousePeople --> Speaker[Speaker & Deputy<br/>Art 93-96]
    end
    
    StatePolicy --> Executive
    CitizenDuties --> Parliament
    Executive --> Parliament
    
    classDef principles fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef duties fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    classDef executive fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef parliament fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef foundation fill:#fff8e1,stroke:#f57f17,stroke-width:3px
    
    class PartIV,DP1,DP2,DP3,DP4,DP5,StatePolicy principles
    class PartIVA,FD1,FD2,FD3,FD4,FD5,CitizenDuties duties
    class Executive,President,VicePresident,CouncilMinisters,AttorneyGeneral,PresidentialPowers,ChairmanRS,PrimeMinister,Ministers executive
    class Parliament,CouncilStates,HousePeople,RSComposition,LSComposition,RSChairman,Speaker parliament
    class Constitution,PartV foundation
```

## Structural Analysis

### Directive Principles Framework
- **Social Welfare**: Articles 38-39 establish state duty for social order
- **Economic Justice**: Articles 39A, 43-43A ensure equal access and worker rights
- **Social Protection**: Articles 46-47 protect weaker sections and public health
- **Cultural-Environmental**: Articles 48A, 49 preserve environment and heritage
- **International Peace**: Article 51 promotes global harmony

### Fundamental Duties Structure
- **Constitutional Loyalty**: Respect for Constitution and national symbols
- **National Integration**: Unity, sovereignty, and common brotherhood
- **Cultural Preservation**: Protection of composite culture and heritage
- **Environmental Responsibility**: Natural environment and wildlife protection
- **Progressive Values**: Scientific temper and excellence in endeavors

### Union Executive Hierarchy
- **President**: Head of State with executive powers and ceremonial functions
- **Vice-President**: Ex-officio Chairman of Council of States
- **Council of Ministers**: Led by Prime Minister, collectively responsible to Lok Sabha
- **Attorney-General**: Chief legal advisor to Government of India

### Parliamentary Structure
- **Bicameral System**: Council of States (Rajya Sabha) and House of the People (Lok Sabha)
- **Representation**: Federal character through state representation and direct election
- **Leadership**: Chairman/Deputy Chairman for Rajya Sabha, Speaker/Deputy Speaker for Lok Sabha
- **Duration**: Rajya Sabha permanent with 1/3 retirement every 2 years, Lok Sabha 5-year term

## Constitutional Integration
The diagram illustrates how Directive Principles guide state policy, Fundamental Duties bind citizens, and the Union structure implements governance through executive and legislative branches, creating a comprehensive framework for democratic governance in India.