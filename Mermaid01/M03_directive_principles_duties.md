# Directive Principles and Fundamental Duties - Task 004

## Source
Lines 301-400 from Constitution of India text
Task 004 - Directive Principles, Fundamental Duties, and Union Executive Structure

## Mermaid Diagram

```mermaid
graph TD
    %% Main constitutional progression
    DP[PART IV: DIRECTIVE PRINCIPLES]
    DP --> SocJust[Social & Economic Justice]
    
    %% Social Justice - Horizontal flow
    subgraph "Social & Economic Justice"
        direction LR
        SocJust --> A1[Art 40:<br/>Village Panchayats] --> A2[Art 41:<br/>Work & Education] --> A3[Art 42:<br/>Work Conditions] --> A4[Art 43:<br/>Living Wage]
    end
    
    subgraph "Economic Democracy"
        direction LR
        A4 --> A5[Art 43A:<br/>Worker Participation] --> A6[Art 43B:<br/>Cooperatives] --> A7[Art 44:<br/>Uniform Civil Code]
    end
    
    subgraph "Social Welfare"
        direction LR
        A7 --> A8[Art 45:<br/>Child Education] --> A9[Art 46:<br/>SC/ST Welfare] --> A10[Art 47:<br/>Public Health]
    end
    
    %% Administrative Principles - Compact section
    A10 --> Admin[Administrative Principles]
    subgraph "Administrative Framework"
        direction LR
        Admin --> B1[Art 48:<br/>Agriculture] --> B2[Art 48A:<br/>Environment] --> B3[Art 49:<br/>Monuments] --> B4[Art 50:<br/>Judicial Independence]
    end
    
    %% International Relations
    B4 --> Intl[International Relations]
    subgraph "Global Engagement"
        Intl --> C1[Art 51:<br/>Peace & Security]
    end
    
    %% Fundamental Duties
    C1 --> FD[PART IVA: FUNDAMENTAL DUTIES]
    subgraph "Citizen Responsibilities"
        FD --> D1[Art 51A:<br/>Citizen Duties]
    end
    
    %% Union Executive Structure
    D1 --> UE[PART V: THE UNION EXECUTIVE]
    UE --> PresOff[Presidential Office]
    
    %% Presidential Framework - Vertical branching
    subgraph "Presidential System"
        PresOff --> E1[Art 52: President of India]
        E1 --> E2[Art 53: Executive Power]
        E1 --> E3[Art 54: Election Process]
        E2 --> E4[Art 55: Election Manner]
        E3 --> E4
    end
    
    subgraph "Presidential Terms & Conditions"
        direction LR
        E4 --> E5[Art 56:<br/>Term of Office] --> E6[Art 57:<br/>Re-election] --> E7[Art 58:<br/>Qualifications]
    end
    
    subgraph "Presidential Operations"
        direction LR
        E7 --> E8[Art 59:<br/>Office Conditions] --> E9[Art 60:<br/>Oath] --> E10[Art 61:<br/>Impeachment]
    end
    
    %% Vice-Presidential Office
    E10 --> VPOff[Vice-Presidential Office]
    subgraph "Vice-Presidential Framework"
        direction LR
        VPOff --> F1[Art 62:<br/>VP Election Timing] --> F2[Art 63:<br/>VP of India] --> F3[Art 64:<br/>Ex-officio Chairman] --> F4[Art 65:<br/>Acting President]
    end
    
    %% Mobile-friendly styling
    classDef partHeader fill:#f3e5f5,stroke:#7b1fa2,stroke-width:3px,font-weight:bold
    classDef sectionHeader fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef social fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef admin fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    classDef international fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
    classDef duties fill:#fce4ec,stroke:#c2185b,stroke-width:2px
    classDef president fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef vp fill:#f1f8e9,stroke:#388e3c,stroke-width:2px
    
    class DP,FD,UE partHeader
    class SocJust,Admin,Intl,PresOff,VPOff sectionHeader
    class A1,A2,A3,A4,A5,A6,A7,A8,A9,A10 social
    class B1,B2,B3,B4 admin
    class C1 international
    class D1 duties
    class E1,E2,E3,E4,E5,E6,E7,E8,E9,E10 president
    class F1,F2,F3,F4 vp
```

## Analysis Notes

This section reveals three critical components of the constitutional framework:

### Part IV: Directive Principles of State Policy
**Social and Economic Justice Principles:**
- **Local Governance**: Village panchayats (Art 40)
- **Economic Rights**: Work, education, living wage (Arts 41-43)
- **Industrial Democracy**: Worker participation (Art 43A)
- **Cooperative Movement**: Promotion of cooperatives (Art 43B)
- **Social Reform**: Uniform civil code (Art 44)
- **Education**: Early childhood care (Art 45)
- **Social Justice**: SC/ST welfare (Art 46)
- **Public Health**: Nutrition and healthcare (Art 47)

**Administrative and Environmental Principles:**
- **Agriculture**: Rural development focus (Art 48)
- **Environment**: Wildlife and forest protection (Art 48A)
- **Heritage**: Monument protection (Art 49)
- **Judicial Independence**: Separation of powers (Art 50)

**International Relations:**
- **Peace**: International cooperation (Art 51)

### Part IVA: Fundamental Duties
- **Citizen Responsibilities**: Balances fundamental rights with duties (Art 51A)

### Part V: The Union - Executive Structure
**Presidential System Framework:**
- **Head of State**: President as constitutional head
- **Executive Power**: Vested in President but exercised through Council of Ministers
- **Electoral Process**: Indirect election through electoral college
- **Term and Qualifications**: Specific constitutional requirements
- **Accountability**: Impeachment provisions

## Constitutional Significance

This structure establishes:
1. **Welfare State Vision**: Comprehensive directive principles for social justice
2. **Balanced Citizenship**: Rights complemented by duties
3. **Executive Framework**: Presidential system with parliamentary features
4. **Separation of Powers**: Clear distinction between executive and judiciary

The transition from non-justiciable principles to justiciable duties to actual government structure shows the Constitution's comprehensive approach to governance.