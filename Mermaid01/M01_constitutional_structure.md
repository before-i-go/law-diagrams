# Constitutional Structure Overview - Task 002

## Source
Lines 101-200 from Constitution of India text
Task 002 - Table of Contents Analysis

## Mermaid Diagram

```mermaid
graph TD
    subgraph "Constitutional Foundation"
        A[Constitution of India]
        B[Preamble]
    end
    
    subgraph "Part I: Union & Territory"
        C1[Art 1: Name & Territory]
        C2[Art 2: New States]
        C3[Art 3: State Formation]
        C4[Art 4: Schedule Amendment]
    end
    
    subgraph "Part II: Citizenship"
        D1[Art 5: Citizenship at Commencement]
        D2[Art 6: Pakistan Migrants Rights]
        D3[Art 7: Migrants to Pakistan]
        D4[Art 8: Indian Origin Abroad]
        D5[Art 9: Foreign Citizenship Bar]
        D6[Art 10: Rights Continuance]
        D7[Art 11: Parliamentary Regulation]
    end
    
    subgraph "Part III: Fundamental Rights"
        direction TD
        E1[General Provisions<br/>Art 12-13]
        E2[Right to Equality<br/>Art 14-18]
        E3[Right to Freedom<br/>Art 19-22]
        
        E1 --> E2
        E2 --> E3
    end
    
    A --> B
    A --> C1
    C1 --> C2
    C2 --> C3
    C3 --> C4
    C4 --> D1
    D1 --> D2
    D2 --> D3
    D3 --> D4
    D4 --> D5
    D5 --> D6
    D6 --> D7
    D7 --> E1
    
    classDef foundation fill:#e1f5fe
    classDef territory fill:#e8f5e8
    classDef citizenship fill:#fff3e0
    classDef rights fill:#fce4ec
    
    class A,B foundation
    class C1,C2,C3,C4 territory
    class D1,D2,D3,D4,D5,D6,D7 citizenship
    class E1,E2,E3 rights
```

## Analysis Notes

This section provides the foundational structure of the Indian Constitution, showing:

1. **Hierarchical Organization**: The Constitution is systematically organized into Parts
2. **Territorial Framework**: Part I establishes the Union and state formation mechanisms
3. **Citizenship Framework**: Part II defines who are citizens and their rights
4. **Rights Framework**: Part III begins the fundamental rights structure

The diagram shows the logical flow from basic territorial organization to citizenship to fundamental rights, establishing the constitutional hierarchy.

## Key Constitutional Concepts Identified

- **Federal Structure**: Articles 1-4 establish the Union and mechanisms for state creation/modification
- **Citizenship Regime**: Articles 5-11 create comprehensive citizenship framework
- **Rights Architecture**: Articles 12+ establish fundamental rights with clear categorization
- **Systematic Organization**: Clear part-wise division showing constitutional logic

This structure forms the foundation for understanding the entire constitutional framework.