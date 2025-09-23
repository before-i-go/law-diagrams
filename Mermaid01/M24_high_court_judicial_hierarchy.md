# High Court and Judicial Hierarchy Structure

## Overview
This diagram illustrates the structure and hierarchy of High Courts in India, including their appointment procedures, jurisdiction, powers, and relationship with subordinate courts as outlined in Part VI, Chapter V of the Constitution.

## Key Articles Covered
- **Articles 214-232**: High Courts in the States
- **Articles 233-236**: Subordinate Courts
- **Article 226**: Writ jurisdiction of High Courts
- **Article 227**: Superintendence over subordinate courts

## Constitutional Significance
High Courts serve as the principal courts of the states, exercising both original and appellate jurisdiction. They have constitutional powers to issue writs for enforcement of fundamental rights and exercise superintendence over all subordinate courts within their territorial jurisdiction.

```mermaid
graph TD
    subgraph "Constitutional Framework"
        Constitution[Constitution of India<br/>Part VI: The States]
        Constitution --> HighCourtChapter[Chapter V: High Courts<br/>Articles 214-232]
        Constitution --> SubordinateChapter[Chapter VI: Subordinate Courts<br/>Articles 233-236]
    end
    
    subgraph "High Court Structure"
        HighCourtChapter --> HCEstablishment[High Court Establishment<br/>Art 214: One for each State]
        HCEstablishment --> HCComposition[High Court Composition<br/>Art 216: Chief Justice + Other Judges]
        
        HCComposition --> ChiefJustice[Chief Justice]
        HCComposition --> OtherJudges[Other Judges<br/>As appointed by President]
        HCComposition --> AdditionalJudges[Additional Judges<br/>Art 224: Temporary appointments]
        HCComposition --> ActingJudges[Acting Judges<br/>Art 224: Temporary duties]
    end
    
    subgraph "Appointment Process"
        HCComposition --> AppointmentAuth[Appointment Authority<br/>Art 217: President of India]
        AppointmentAuth --> Qualifications[Qualifications<br/>Art 217(2)]
        Qualifications --> Qual1[Citizen of India]
        Qualifications --> Qual2[10 years judicial office OR<br/>10 years High Court advocate]
        
        AppointmentAuth --> Tenure[Tenure<br/>Until age 62 years]
        AppointmentAuth --> Removal[Removal<br/>Same as Supreme Court Judges]
    end
    
    subgraph "High Court Powers"
        HCComposition --> OriginalJurisdiction[Original Jurisdiction<br/>Art 225: As existing before Constitution]
        HCComposition --> WritJurisdiction[Writ Jurisdiction<br/>Art 226]
        
        WritJurisdiction --> WritTypes[Writ Types]
        WritTypes --> HabeasCorpus[Habeas Corpus]
        WritTypes --> Mandamus[Mandamus]
        WritTypes --> Prohibition[Prohibition]
        WritTypes --> Certiorari[Certiorari]
        WritTypes --> QuoWarranto[Quo Warranto]
        
        HCComposition --> Superintendence[Superintendence Power<br/>Art 227: Over all subordinate courts]
    end
    
    subgraph "Subordinate Court Hierarchy"
        SubordinateChapter --> DistrictCourts[District Courts<br/>Art 233: District Judges]
        DistrictCourts --> DistrictJudgeAppt[District Judge Appointment<br/>Governor + High Court consultation]
        
        DistrictCourts --> SubordinateCourts[Courts Subordinate to District Courts]
        SubordinateCourts --> CivilCourts[Civil Courts]
        SubordinateCourts --> CriminalCourts[Criminal Courts]
        SubordinateCourts --> SpecialCourts[Special Courts]
        
        DistrictCourts --> JudicialService[Judicial Service<br/>Art 234: Other judicial officers]
        JudicialService --> ServiceAppt[Appointment: Governor +<br/>State PSC + High Court]
    end
    
    subgraph "Administrative Control"
        Superintendence --> AdminControl[Administrative Control<br/>Art 235]
        AdminControl --> HCControl[High Court Controls:]
        HCControl --> Posting[Posting & Promotion]
        HCControl --> Leave[Grant of Leave]
        HCControl --> Discipline[Disciplinary Matters]
        
        AdminControl --> ServiceConditions[Service Conditions<br/>As per law]
    end
    
    subgraph "Special Provisions"
        HCComposition --> Transfer[Transfer of Judges<br/>Art 222: Between High Courts]
        HCComposition --> ActingCJ[Acting Chief Justice<br/>Art 223: When CJ absent]
        HCComposition --> RetiredJudges[Retired Judges<br/>Art 224A: Sitting arrangements]
        
        HighCourtChapter --> CommonHC[Common High Court<br/>Art 231: For multiple States]
        HighCourtChapter --> UTJurisdiction[Union Territory Jurisdiction<br/>Art 230: Extension by Parliament]
    end
    
    %% Connections showing hierarchy and control
    Superintendence --> DistrictCourts
    DistrictCourts --> SubordinateCourts
    AdminControl --> JudicialService
    
    %% Styling
    classDef foundation fill:#e1f5fe,stroke:#01579b,stroke-width:3px
    classDef structure fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    classDef powers fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef process fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    classDef hierarchy fill:#fce4ec,stroke:#c2185b,stroke-width:2px
    
    class Constitution,HighCourtChapter,SubordinateChapter foundation
    class HCEstablishment,HCComposition,DistrictCourts structure
    class WritJurisdiction,Superintendence,AdminControl powers
    class AppointmentAuth,DistrictJudgeAppt,ServiceAppt process
    class SubordinateCourts,JudicialService hierarchy
```

## Judicial Hierarchy Flow

The constitutional framework establishes a clear judicial hierarchy:

1. **High Court Level**: Constitutional courts with original and appellate jurisdiction
2. **District Court Level**: Principal trial courts with civil and criminal jurisdiction  
3. **Subordinate Court Level**: Various specialized and lower courts under district court supervision

## Key Constitutional Features

### High Court Powers
- **Writ Jurisdiction**: Constitutional remedy for fundamental rights violations
- **Superintendence**: Administrative and judicial control over subordinate courts
- **Original Jurisdiction**: Direct hearing of certain matters
- **Appellate Jurisdiction**: Review of lower court decisions

### Appointment Mechanisms
- **High Court Judges**: Presidential appointment with constitutional consultation
- **District Judges**: Governor appointment with High Court consultation
- **Other Judicial Officers**: Governor appointment with State PSC and High Court consultation

### Administrative Structure
- **Unified Control**: High Court exercises superintendence over entire subordinate judiciary
- **Service Conditions**: Governed by law with High Court administrative control
- **Career Progression**: Structured promotion and posting system under High Court supervision

This structure ensures judicial independence while maintaining administrative efficiency and constitutional oversight of the state judicial system.