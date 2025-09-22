# State Legislative Procedures and High Courts

## Overview
This diagram illustrates the legislative procedures in State Legislatures and the introduction of High Courts as outlined in Articles 196-217 of the Constitution of India.

## Mermaid Diagram

```mermaid
graph TD
    %% State Legislative Procedures Foundation
    SLP[STATE LEGISLATIVE PROCEDURES]
    SLP --> LegislativeProcedure[Legislative Procedure]
    
    %% Legislative Process - Horizontal flow
    subgraph "Bill Process Framework"
        direction LR
        LegislativeProcedure --> A1[Art 196:<br/>Bill Introduction<br/>& Passing] --> A2[Art 197:<br/>Legislative Council<br/>Restrictions] --> A3[Art 198:<br/>Money Bill<br/>Procedure]
    end
    
    subgraph "Bill Completion"
        direction LR
        A3 --> A4[Art 199:<br/>Money Bill<br/>Definition] --> A5[Art 200:<br/>Governor's<br/>Assent] --> A6[Art 201:<br/>Bills Reserved<br/>for President]
    end
    
    %% Financial Procedures - Horizontal flow
    A6 --> FinancialProcedures[State Financial Procedures]
    subgraph "Budget Framework"
        direction LR
        FinancialProcedures --> B1[Art 202:<br/>Annual Financial<br/>Statement] --> B2[Art 203:<br/>Estimates<br/>Procedure] --> B3[Art 204:<br/>Appropriation<br/>Bills]
    end
    
    subgraph "Financial Controls"
        direction LR
        B3 --> B4[Art 205:<br/>Supplementary<br/>Grants] --> B5[Art 206:<br/>Votes of Credit] --> B6[Art 207:<br/>Financial Bill<br/>Provisions]
    end
    
    %% General Procedures
    B6 --> GeneralProcedures[General Legislative Procedures]
    subgraph "Operational Rules"
        direction LR
        GeneralProcedures --> C1[Art 208:<br/>Rules of<br/>Procedure] --> C2[Art 209:<br/>Financial Business<br/>Regulation] --> C3[Art 210:<br/>Legislature<br/>Language]
    end
    
    subgraph "Procedural Limits"
        direction LR
        C3 --> C4[Art 211:<br/>Discussion<br/>Restrictions] --> C5[Art 212:<br/>Court Inquiry<br/>Bar]
    end
    
    %% Governor's Powers
    C5 --> GovernorPowers[Governor's Legislative Powers]
    subgraph "Emergency Legislation"
        GovernorPowers --> D1[Art 213:<br/>Ordinance Power<br/>During Recess]
    end
    
    %% High Courts Introduction
    D1 --> HighCourts[High Courts Framework]
    subgraph "State Judiciary"
        direction LR
        HighCourts --> E1[Art 214:<br/>High Courts<br/>for States] --> E2[Art 215:<br/>Courts of Record<br/>Status]
    end
    
    subgraph "Court Structure"
        direction LR
        E2 --> E3[Art 216:<br/>HC Constitution] --> E4[Art 217:<br/>Judge Appointment<br/>& Conditions]
    end
    
    %% Process Flows - Vertical branching
    E4 --> ProcessFlows[Process Flows]
    subgraph "Legislative Process Flow"
        ProcessFlows --> F1[Bill Introduction]
        F1 --> F2[Assembly Consideration]
        F1 --> F3[Council Review (if bicameral)]
        F2 --> F4[Governor's Assent/Reserve]
        F3 --> F4
        F4 --> F5[Presidential Consideration (if reserved)]
        F5 --> F6[Law Enactment]
    end
    
    subgraph "Financial Process Flow"
        ProcessFlows --> G1[Budget Presentation]
        G1 --> G2[Legislative Approval]
        G2 --> G3[Appropriation]
        G3 --> G4[Supplementary Demands]
        G4 --> G5[Audit & Review]
    end
    
    %% Mobile-friendly styling
    classDef partHeader fill:#f3e5f5,stroke:#7b1fa2,stroke-width:3px,font-weight:bold
    classDef sectionHeader fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef legislative fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef financial fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef general fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef governor fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    classDef courts fill:#fce4ec,stroke:#c2185b,stroke-width:2px
    classDef process fill:#f1f8e9,stroke:#388e3c,stroke-width:2px
    classDef finprocess fill:#fff8e1,stroke:#f57f17,stroke-width:2px
    
    class SLP partHeader
    class LegislativeProcedure,FinancialProcedures,GeneralProcedures,GovernorPowers,HighCourts,ProcessFlows sectionHeader
    class A1,A2,A3,A4,A5,A6 legislative
    class B1,B2,B3,B4,B5,B6 financial
    class C1,C2,C3,C4,C5 general
    class D1 governor
    class E1,E2,E3,E4 courts
    class F1,F2,F3,F4,F5,F6 process
    class G1,G2,G3,G4,G5 finprocess
```

## Key Constitutional Articles Covered

### State Legislative Procedure (Articles 196-201)
- **Article 196**: Provisions for introduction and passing of Bills
- **Article 197**: Restriction on Legislative Council powers (similar to Rajya Sabha limitations)
- **Article 198**: Special procedure for Money Bills in states
- **Article 199**: Definition of "Money Bills" at state level
- **Article 200**: Governor's assent to Bills
- **Article 201**: Bills reserved for Presidential consideration

### State Financial Procedures (Articles 202-207)
- **Article 202**: Annual Financial Statement (State Budget)
- **Article 203**: Procedure in Legislature regarding estimates
- **Article 204**: Appropriation Bills for state expenditure
- **Article 205**: Supplementary, additional, or excess grants
- **Article 206**: Votes on account, votes of credit, exceptional grants
- **Article 207**: Special provisions for financial Bills

### General Legislative Procedures (Articles 208-212)
- **Article 208**: Rules of procedure for state legislatures
- **Article 209**: Regulation by law of financial business procedure
- **Article 210**: Language to be used in Legislature
- **Article 211**: Restriction on discussion in Legislature
- **Article 212**: Courts not to inquire into legislative proceedings

### Governor's Legislative Powers (Article 213)
- **Article 213**: Power to promulgate Ordinances during Legislature recess

### High Courts Framework (Articles 214-217)
- **Article 214**: High Courts for States (establishment)
- **Article 215**: High Courts as courts of record
- **Article 216**: Constitution of High Courts
- **Article 217**: Appointment and conditions of High Court Judges

## Legislative Process Summary

### Ordinary Bills:
1. **Introduction** → Assembly consideration → Council review (if applicable) → Governor's assent
2. **If Reserved** → Presidential consideration → Assent/withholding

### Money Bills:
1. **Assembly Introduction** → Limited Council powers → Governor's assent
2. **Special Procedure** → Financial scrutiny → Appropriation

### Financial Process:
1. **Budget Presentation** → Legislative approval → Appropriation → Implementation
2. **Supplementary Demands** → Additional approvals → Revised appropriation

## Parallel with Union Procedures
State procedures mirror Union Parliament:
- **Bill Process** ↔ Parliamentary procedure
- **Money Bills** ↔ Lok Sabha primacy
- **Financial Statement** ↔ Union Budget
- **Governor's Assent** ↔ Presidential Assent
- **Ordinance Power** ↔ Presidential Ordinances

## High Courts Introduction
- **State Judiciary**: High Courts as principal courts for states
- **Constitutional Status**: Courts of record with inherent powers
- **Federal Integration**: Part of unified judicial system
- **Appointment Process**: Central government involvement in judge selection

## Significance
This framework establishes:
- **Legislative Autonomy**: States can make laws on state subjects
- **Financial Control**: Democratic oversight of state finances
- **Constitutional Limits**: Governor and Presidential oversight
- **Judicial Independence**: High Courts as constitutional courts
- **Federal Balance**: State autonomy within constitutional framework
- **Democratic Accountability**: Legislative control over executive actions