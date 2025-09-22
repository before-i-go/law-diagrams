# State Legislative Procedures and High Courts

## Overview
This diagram illustrates the legislative procedures in State Legislatures and the introduction of High Courts as outlined in Articles 196-217 of the Constitution of India.

## Mermaid Diagram

```mermaid
graph TD
    subgraph "State Legislative Procedure"
        direction TD
        A1[Art 196: Bill Introduction & Passing]
        A2[Art 197: Legislative Council Restrictions]
        A3[Art 198: Money Bill Procedure]
        A4[Art 199: Money Bill Definition]
        A5[Art 200: Governor's Assent]
        A6[Art 201: Bills Reserved for President]
    end
    
    subgraph "State Financial Procedures"
        direction TD
        B1[Art 202: Annual Financial Statement]
        B2[Art 203: Estimates Procedure]
        B3[Art 204: Appropriation Bills]
        B4[Art 205: Supplementary Grants]
        B5[Art 206: Votes of Credit]
        B6[Art 207: Financial Bill Provisions]
    end
    
    subgraph "General Legislative Procedures"
        direction TD
        C1[Art 208: Rules of Procedure]
        C2[Art 209: Financial Business Regulation]
        C3[Art 210: Legislature Language]
        C4[Art 211: Discussion Restrictions]
        C5[Art 212: Court Inquiry Bar]
    end
    
    subgraph "Governor's Legislative Powers"
        direction TD
        D1[Art 213: Ordinance Power During Recess]
    end
    
    subgraph "High Courts Framework"
        direction TD
        E1[Art 214: High Courts for States]
        E2[Art 215: Courts of Record Status]
        E3[Art 216: HC Constitution]
        E4[Art 217: Judge Appointment & Conditions]
    end
    
    subgraph "Legislative Process Flow"
        direction TD
        F1[Bill Introduction]
        F2[Assembly Consideration]
        F3[Council Review (if bicameral)]
        F4[Governor's Assent/Reserve]
        F5[Presidential Consideration (if reserved)]
        F6[Law Enactment]
    end
    
    subgraph "Financial Process Flow"
        direction TD
        G1[Budget Presentation]
        G2[Legislative Approval]
        G3[Appropriation]
        G4[Supplementary Demands]
        G5[Audit & Review]
    end

    A1 --> A2 --> A3 --> A4 --> A5 --> A6
    A6 --> B1
    B1 --> B2 --> B3 --> B4 --> B5 --> B6
    B6 --> C1 --> C2 --> C3 --> C4 --> C5
    C5 --> D1
    D1 --> E1 --> E2 --> E3 --> E4
    
    %% Process flows
    A1 --> F1
    F1 --> F2 --> F3 --> F4 --> F5 --> F6
    
    B1 --> G1
    G1 --> G2 --> G3 --> G4 --> G5

    classDef legislative fill:#e1f5fe
    classDef financial fill:#f3e5f5
    classDef general fill:#e8f5e8
    classDef governor fill:#fff3e0
    classDef courts fill:#fce4ec
    classDef process fill:#f1f8e9
    classDef finprocess fill:#fff8e1

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