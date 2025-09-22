# Supreme Court Structure and Judicial System

## Overview
This diagram illustrates the structure, powers, and functioning of India's Supreme Court and related judicial provisions as outlined in Articles 124-147 of the Constitution of India.

## Mermaid Diagram

```mermaid
graph TD
    %% Supreme Court Foundation
    SC[SUPREME COURT STRUCTURE]
    SC --> Establishment[Supreme Court Establishment]
    
    %% Establishment - Horizontal flow
    subgraph "Constitutional Foundation"
        direction LR
        Establishment --> A1[Art 124:<br/>SC Constitution] --> A2[Art 129:<br/>Court of Record] --> A3[Art 130:<br/>Seat of SC]
    end
    
    subgraph "Administrative Framework"
        direction LR
        A3 --> A4[Art 146:<br/>Officers & Expenses] --> A5[Art 147:<br/>Interpretation]
    end
    
    %% Judicial Appointments - Mixed layout
    A5 --> Appointments[Judicial Appointments]
    subgraph "Appointment Commission"
        direction LR
        Appointments --> B1[Art 124A:<br/>NJAC] --> B2[Art 124B:<br/>Commission Functions] --> B3[Art 124C:<br/>Parliamentary Powers]
    end
    
    subgraph "Judge Conditions"
        direction LR
        B3 --> B4[Art 125:<br/>Judge Salaries] --> B5[Art 126:<br/>Acting Chief Justice]
    end
    
    subgraph "Special Appointments"
        direction LR
        B5 --> B6[Art 127:<br/>Ad Hoc Judges] --> B7[Art 128:<br/>Retired Judge<br/>Attendance]
    end
    
    %% Supreme Court Jurisdiction - Vertical expansion
    B7 --> Jurisdiction[Supreme Court Jurisdiction]
    subgraph "Core Jurisdiction"
        Jurisdiction --> C1[Art 131: Original Jurisdiction]
        Jurisdiction --> C2[Art 132: Constitutional Appeals]
        C1 --> C3[Art 133: Civil Appeals]
        C2 --> C4[Art 134: Criminal Appeals]
    end
    
    subgraph "Extended Jurisdiction"
        direction LR
        C3 --> C5[Art 134A:<br/>Appeal Certificate] --> C6[Art 135:<br/>Federal Court Powers] --> C7[Art 136:<br/>Special Leave]
    end
    
    subgraph "Judicial Powers"
        direction LR
        C7 --> C8[Art 137:<br/>Review Powers] --> C9[Art 138:<br/>Jurisdiction<br/>Enlargement]
    end
    
    %% Writ Powers & Enforcement
    C9 --> WritPowers[Writ Powers & Enforcement]
    subgraph "Constitutional Remedies"
        direction LR
        WritPowers --> D1[Art 139:<br/>Writ Powers] --> D2[Art 139A:<br/>Case Transfer] --> D3[Art 140:<br/>Ancillary Powers]
    end
    
    subgraph "Enforcement Authority"
        direction LR
        D3 --> D4[Art 141:<br/>Binding Precedent] --> D5[Art 142:<br/>Decree Enforcement]
    end
    
    %% Advisory & Administrative
    D5 --> Advisory[Advisory & Administrative]
    subgraph "Advisory Functions"
        direction LR
        Advisory --> E1[Art 143:<br/>Presidential<br/>Consultation] --> E2[Art 144:<br/>Authorities Aid SC] --> E3[Art 145:<br/>Rules of Court]
    end
    
    %% Comptroller & Auditor-General
    E3 --> CAG[Comptroller & Auditor-General]
    subgraph "Financial Oversight"
        direction LR
        CAG --> F1[Art 148:<br/>CAG Appointment] --> F2[Art 149:<br/>CAG Duties<br/>& Powers]
    end
    
    subgraph "Audit Framework"
        direction LR
        F2 --> F3[Art 150:<br/>Accounts Form] --> F4[Art 151:<br/>Audit Reports]
    end
    
    %% Mobile-friendly styling
    classDef partHeader fill:#f3e5f5,stroke:#7b1fa2,stroke-width:3px,font-weight:bold
    classDef sectionHeader fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef establishment fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
    classDef appointments fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef jurisdiction fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    classDef powers fill:#fce4ec,stroke:#c2185b,stroke-width:2px
    classDef advisory fill:#f1f8e9,stroke:#388e3c,stroke-width:2px
    classDef audit fill:#e0f2f1,stroke:#00695c,stroke-width:2px
    
    class SC partHeader
    class Establishment,Appointments,Jurisdiction,WritPowers,Advisory,CAG sectionHeader
    class A1,A2,A3,A4,A5 establishment
    class B1,B2,B3,B4,B5,B6,B7 appointments
    class C1,C2,C3,C4,C5,C6,C7,C8,C9 jurisdiction
    class D1,D2,D3,D4,D5 powers
    class E1,E2,E3 advisory
    class F1,F2,F3,F4 audit
```

## Key Constitutional Articles Covered

### Supreme Court Establishment (Articles 124-130)
- **Article 124**: Establishment and constitution of Supreme Court
- **Article 124A**: National Judicial Appointments Commission
- **Article 124B**: Functions of the Commission
- **Article 124C**: Power of Parliament to make laws
- **Article 125**: Salaries and conditions of Judges
- **Article 126**: Appointment of acting Chief Justice
- **Article 127**: Appointment of ad hoc Judges
- **Article 128**: Attendance of retired Judges
- **Article 129**: Supreme Court as court of record
- **Article 130**: Seat of Supreme Court

### Supreme Court Jurisdiction (Articles 131-140)
- **Article 131**: Original jurisdiction
- **Article 132**: Appellate jurisdiction (constitutional cases)
- **Article 133**: Appellate jurisdiction (civil matters)
- **Article 134**: Appellate jurisdiction (criminal matters)
- **Article 134A**: Certificate for appeal
- **Article 135**: Federal Court jurisdiction transfer
- **Article 136**: Special leave to appeal
- **Article 137**: Review of judgments
- **Article 138**: Enlargement of jurisdiction
- **Article 139**: Writ powers
- **Article 139A**: Transfer of cases
- **Article 140**: Ancillary powers

### Supreme Court Operations (Articles 141-147)
- **Article 141**: Law declared by Supreme Court binding
- **Article 142**: Enforcement powers and discovery orders
- **Article 143**: Presidential consultation power
- **Article 144**: Civil and judicial authorities to aid Supreme Court
- **Article 145**: Rules of Court
- **Article 146**: Officers, servants, and expenses
- **Article 147**: Interpretation

### Comptroller and Auditor-General (Articles 148-151)
- **Article 148**: CAG appointment and independence
- **Article 149**: Duties and powers of CAG
- **Article 150**: Form of accounts (Union and States)
- **Article 151**: Audit reports to Parliament and State Legislatures

## Judicial Hierarchy and Flow

1. **Appointment Process**: NJAC → Chief Justice → Other Judges
2. **Jurisdictional Flow**: Original → Appellate → Special Leave → Review
3. **Power Exercise**: Constitutional interpretation → Binding precedent → Enforcement
4. **Administrative Support**: Rules → Officers → Civil authorities aid
5. **Financial Oversight**: CAG audit → Reports → Legislative scrutiny

## Significance
This framework establishes:
- **Judicial Independence**: Through secure tenure and salary protection
- **Constitutional Supremacy**: Through judicial review powers
- **Federal Arbitration**: Through original jurisdiction in inter-governmental disputes
- **Legal Uniformity**: Through binding precedent system
- **Financial Accountability**: Through independent audit mechanism
- **Access to Justice**: Through special leave and writ jurisdictions