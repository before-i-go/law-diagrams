# Executive and Parliament Structure - Task 005

## Source
Lines 401-500 from Constitution of India text
Task 005 - Complete Executive Structure and Parliament Framework

## Mermaid Diagram

```mermaid
graph TD
    subgraph "Union Executive Structure"
        direction TD
        
        subgraph "Presidential Office"
            A1[Art 61: Impeachment]
            A2[Art 62: Election Timing]
            A3[Art 72: Pardoning Power]
            A4[Art 73: Executive Power Extent]
        end
        
        subgraph "Vice-Presidential Office"
            B1[Art 63: VP of India]
            B2[Art 64: Rajya Sabha Chairman]
            B3[Art 65: Acting President]
            B4[Art 66: VP Election]
            B5[Art 67: VP Term]
            B6[Art 68: VP Election Timing]
            B7[Art 69: VP Oath]
            B8[Art 70: Presidential Functions]
            B9[Art 71: Election Matters]
        end
        
        subgraph "Council of Ministers"
            C1[Art 74: Aid & Advise President]
            C2[Art 75: Minister Provisions]
        end
        
        subgraph "Legal Officer"
            D1[Art 76: Attorney-General]
        end
        
        subgraph "Government Business"
            E1[Art 77: Business Conduct]
            E2[Art 78: PM Duties to President]
        end
    end
    
    subgraph "Parliament Structure"
        direction TD
        
        subgraph "Constitutional Framework"
            F1[Art 79: Parliament Constitution]
            F2[Art 80: Rajya Sabha Composition]
            F3[Art 81: Lok Sabha Composition]
            F4[Art 82: Census Readjustment]
            F5[Art 83: House Duration]
            F6[Art 84: Membership Qualification]
            F7[Art 85: Sessions & Dissolution]
            F8[Art 86: Presidential Address]
            F9[Art 87: Special Address]
            F10[Art 88: Minister Rights]
        end
        
        subgraph "Rajya Sabha Officers"
            G1[Art 89: Chairman & Deputy]
            G2[Art 90: Vacation & Resignation]
            G3[Art 91: Deputy Chairman Duties]
            G4[Art 92: Removal Proceedings]
        end
        
        subgraph "Lok Sabha Officers"
            H1[Art 93: Speaker & Deputy]
            H2[Art 94: Vacation Provisions]
            H3[Art 95: Speaker Powers]
        end
    end
    
    subgraph "Executive-Legislative Interface"
        I1[Presidential Address to Parliament]
        I2[Ministerial Participation]
        I3[VP as Rajya Sabha Chairman]
        I4[PM Reports to President]
    end
    
    A1 --> A2 --> A3 --> A4
    A4 --> B1
    B1 --> B2 --> B3 --> B4 --> B5
    B5 --> B6 --> B7 --> B8 --> B9
    B9 --> C1 --> C2
    C2 --> D1
    D1 --> E1 --> E2
    E2 --> F1
    F1 --> F2 --> F3 --> F4 --> F5
    F5 --> F6 --> F7 --> F8 --> F9 --> F10
    F10 --> G1
    G1 --> G2 --> G3 --> G4
    G4 --> H1 --> H2 --> H3
    H3 --> I1
    I1 --> I2 --> I3 --> I4
    
    classDef president fill:#e1f5fe
    classDef vp fill:#f3e5f5
    classDef ministers fill:#e8f5e8
    classDef legal fill:#fff3e0
    classDef business fill:#f1f8e9
    classDef parliament fill:#fce4ec
    classDef rajya fill:#e3f2fd
    classDef lok fill:#fff8e1
    classDef interface fill:#e0f2f1
    
    class A1,A2,A3,A4 president
    class B1,B2,B3,B4,B5,B6,B7,B8,B9 vp
    class C1,C2 ministers
    class D1 legal
    class E1,E2 business
    class F1,F2,F3,F4,F5,F6,F7,F8,F9,F10 parliament
    class G1,G2,G3,G4 rajya
    class H1,H2,H3 lok
    class I1,I2,I3,I4 interface
```

## Analysis Notes

This section reveals the complete structure of India's executive and the beginning of its legislative framework:

### Executive Structure
**Presidential System:**
- **Head of State**: President with ceremonial and constitutional powers
- **Impeachment**: Constitutional accountability mechanism (Art 61)
- **Pardoning Power**: Executive clemency authority (Art 72)
- **Executive Power**: Extent and scope defined (Art 73)

**Vice-Presidential Role:**
- **Dual Function**: Vice-President and ex officio Chairman of Rajya Sabha
- **Succession**: Acting President during vacancy or absence
- **Electoral Process**: Separate election mechanism

**Council of Ministers:**
- **Advisory Role**: Aid and advise the President (Art 74)
- **Collective Responsibility**: Parliamentary system feature
- **Prime Minister**: Key liaison with President (Art 78)

### Parliamentary Structure
**Bicameral Legislature:**
- **Rajya Sabha (Council of States)**: Upper house with state representation
- **Lok Sabha (House of the People)**: Lower house with direct election
- **Constitutional Framework**: Composition, duration, qualifications

**Parliamentary Officers:**
- **Rajya Sabha**: Chairman (Vice-President) and Deputy Chairman
- **Lok Sabha**: Speaker and Deputy Speaker
- **Presiding Authority**: Constitutional provisions for leadership

### Executive-Legislative Interface
**Constitutional Connections:**
- **Presidential Address**: Joint sessions and special addresses
- **Ministerial Participation**: Ministers' rights in both Houses
- **Vice-President's Role**: Bridge between executive and Rajya Sabha
- **Information Flow**: PM's duty to inform President

## Constitutional Significance

This structure establishes:
1. **Parliamentary Democracy**: Executive accountable to legislature
2. **Bicameral System**: Federal representation through Rajya Sabha
3. **Separation with Coordination**: Distinct but interconnected branches
4. **Constitutional Monarchy Model**: President as constitutional head with real power in Council of Ministers

The framework balances federal representation, democratic accountability, and executive efficiency.