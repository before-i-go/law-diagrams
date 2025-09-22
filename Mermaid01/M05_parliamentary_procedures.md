# Parliamentary Procedures and Legislative Process

## Overview
This diagram illustrates the comprehensive parliamentary procedures, legislative processes, and member-related provisions as outlined in Articles 96-117 of the Constitution of India.

## Mermaid Diagram

```mermaid
graph TD
    subgraph "Parliamentary Leadership"
        direction TD
        A1[Art 94: Speaker Vacation & Resignation]
        A2[Art 95: Deputy Speaker Powers]
        A3[Art 96: Cannot Preside Own Removal]
        A4[Art 97: Salaries & Allowances]
        A5[Art 98: Parliament Secretariat]
    end

    subgraph "Business Conduct"
        direction TD
        B1[Art 99: Member Oath/Affirmation]
        B2[Art 100: Voting & Quorum]
    end

    subgraph "Member Disqualifications"
        direction TD
        C1[Art 101: Vacation of Seats]
        C2[Art 102: Disqualification Grounds]
        C3[Art 103: Disqualification Decisions]
        C4[Art 104: Unqualified Participation Penalty]
    end

    subgraph "Powers & Privileges"
        direction TD
        D1[Art 105: House & Member Privileges]
        D2[Art 106: Member Salaries]
    end

    subgraph "Legislative Procedure"
        direction TD
        E1[Art 107: Bill Introduction & Passing]
        E2[Art 108: Joint Sitting]
        E3[Art 109: Money Bill Procedure]
        E4[Art 110: Money Bill Definition]
        E5[Art 111: Presidential Assent]
    end

    subgraph "Financial Procedures"
        direction TD
        F1[Art 112: Annual Financial Statement]
        F2[Art 113: Estimates Procedure]
        F3[Art 114: Appropriation Bills]
        F4[Art 115: Supplementary Grants]
        F5[Art 116: Votes of Credit]
        F6[Art 117: Financial Bill Provisions]
    end

    subgraph "General Procedures"
        direction TD
        G1[Art 118: Rules of Procedure]
        G2[Art 119: Financial Business Regulation]
        G3[Art 120: Language in Parliament]
        G4[Art 121: Discussion Restrictions]
        G5[Art 122: Court Inquiry Bar]
    end

    subgraph "Presidential Powers"
        direction TD
        H1[Art 123: Ordinance Power]
    end

    A1 --> A2 --> A3 --> A4 --> A5
    A5 --> B1 --> B2
    B2 --> C1 --> C2 --> C3 --> C4
    C4 --> D1 --> D2
    D2 --> E1 --> E2 --> E3 --> E4 --> E5
    E5 --> F1 --> F2 --> F3 --> F4 --> F5 --> F6
    F6 --> G1 --> G2 --> G3 --> G4 --> G5
    G5 --> H1

    classDef leadership fill:#e1f5fe
    classDef business fill:#f3e5f5
    classDef disqualification fill:#fff3e0
    classDef powers fill:#e8f5e8
    classDef legislative fill:#fce4ec
    classDef financial fill:#fff8e1
    classDef general fill:#f1f8e9
    classDef presidential fill:#e0f2f1

    class A1,A2,A3,A4,A5 leadership
    class B1,B2 business
    class C1,C2,C3,C4 disqualification
    class D1,D2 powers
    class E1,E2,E3,E4,E5 legislative
    class F1,F2,F3,F4,F5,F6 financial
    class G1,G2,G3,G4,G5 general
    class H1 presidential
```

## Key Constitutional Articles Covered

### Parliamentary Leadership (Articles 94-98)
- **Article 94**: Vacation and resignation of Speaker and Deputy Speaker
- **Article 95**: Power of Deputy Speaker to perform Speaker's duties
- **Article 96**: Speaker cannot preside during own removal proceedings
- **Article 97**: Salaries and allowances of presiding officers
- **Article 98**: Parliament Secretariat

### Conduct of Business (Articles 99-100)
- **Article 99**: Oath or affirmation by members
- **Article 100**: Voting procedures, quorum, and power to act despite vacancies

### Member Disqualifications (Articles 101-104)
- **Article 101**: Vacation of seats
- **Article 102**: Grounds for disqualification
- **Article 103**: Decision process for disqualification questions
- **Article 104**: Penalties for unqualified participation

### Powers and Privileges (Articles 105-106)
- **Article 105**: Powers, privileges, and immunities of Parliament and members
- **Article 106**: Salaries and allowances of members

### Legislative Procedure (Articles 107-111)
- **Article 107**: Provisions for introduction and passing of Bills
- **Article 108**: Joint sitting procedures for deadlocked Bills
- **Article 109**: Special procedure for Money Bills
- **Article 110**: Definition of Money Bills
- **Article 111**: Presidential assent to Bills

### Financial Procedures (Articles 112-117)
- **Article 112**: Annual Financial Statement (Budget)
- **Article 113**: Procedure for estimates in Parliament
- **Article 114**: Appropriation Bills
- **Article 115**: Supplementary, additional, or excess grants
- **Article 116**: Votes of credit and exceptional grants
- **Article 117**: Special provisions for financial Bills

## Process Flow Summary

1. **Member Qualification**: Members take oath → Qualified to participate
2. **Legislative Process**: Bill introduction → House procedures → Joint sitting (if needed) → Presidential assent
3. **Financial Process**: Budget presentation → Parliamentary approval → Appropriation
4. **Oversight**: Powers and privileges ensure effective functioning
5. **Support**: Parliamentary secretariat provides administrative backbone

## Significance
This framework establishes the operational mechanics of India's parliamentary democracy, ensuring:
- Proper conduct of legislative business
- Financial accountability and control
- Member qualification and conduct standards
- Institutional privileges and protections
- Systematic law-making processes