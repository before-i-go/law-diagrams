# Judicial Hierarchy and Union Territories Structure

## Overview
This diagram illustrates the judicial hierarchy structure and the administrative framework for Union Territories, Scheduled Areas, and Tribal Areas as established in the Fourth, Fifth, and Sixth Schedules of the Constitution of India.

## Constitutional Framework

```mermaid
graph TD
    Constitution[Constitution of India]
    Constitution --> Schedules[Constitutional Schedules]
    
    subgraph "Fourth Schedule - Rajya Sabha Representation"
        Schedules --> FourthSch[Fourth Schedule<br/>Art 4(1) & 80(2)]
        FourthSch --> States[States Representation]
        FourthSch --> UTs[Union Territories<br/>Representation]
        States --> StateSeats[State-wise Seats<br/>Total: 233]
        UTs --> UTSeats[UT Seats<br/>Delhi: 3, Puducherry: 1<br/>J&K: 4]
    end
    
    subgraph "Fifth Schedule - Scheduled Areas"
        Schedules --> FifthSch[Fifth Schedule<br/>Art 244(1)]
        FifthSch --> ScheduledAreas[Scheduled Areas<br/>Administration]
        ScheduledAreas --> Governor[Governor Powers<br/>Art 244(1)]
        ScheduledAreas --> TAC[Tribes Advisory Council<br/>Max 20 members]
        Governor --> Regulations[Governor Regulations<br/>Peace & Good Govt]
        TAC --> TribalWelfare[Tribal Welfare<br/>Advisory Role]
    end
    
    subgraph "Sixth Schedule - Autonomous Districts"
        Schedules --> SixthSch[Sixth Schedule<br/>Art 244(2) & 275(1)]
        SixthSch --> TribalAreas[Tribal Areas<br/>Assam, Meghalaya, Tripura, Mizoram]
        TribalAreas --> AutonomousDistricts[Autonomous Districts]
        TribalAreas --> AutonomousRegions[Autonomous Regions]
        
        AutonomousDistricts --> DistrictCouncils[District Councils<br/>Max 30 members]
        AutonomousRegions --> RegionalCouncils[Regional Councils<br/>Separate for each region]
        
        DistrictCouncils --> DCPowers[District Council Powers<br/>Land, Forest, Village Admin]
        RegionalCouncils --> RCPowers[Regional Council Powers<br/>Local Administration]
        
        DCPowers --> VillageCourts[Village Courts<br/>Tribal Justice System]
        RCPowers --> TribalLaws[Tribal Laws<br/>Marriage, Inheritance, Customs]
    end
    
    subgraph "Judicial Hierarchy"
        VillageCourts --> AppealCourts[Appeal Courts<br/>District/Regional Councils]
        AppealCourts --> HighCourt[High Court<br/>Limited Jurisdiction]
        HighCourt --> SupremeCourt[Supreme Court<br/>Final Appeal]
    end
    
    classDef schedule fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    classDef council fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px
    classDef court fill:#fce4ec,stroke:#c2185b,stroke-width:2px
    classDef power fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    
    class FourthSch,FifthSch,SixthSch schedule
    class TAC,DistrictCouncils,RegionalCouncils council
    class VillageCourts,AppealCourts,HighCourt,SupremeCourt court
    class Governor,DCPowers,RCPowers,Regulations power
```

## Key Articles Covered

### Fourth Schedule (Articles 4(1) and 80(2))
- **Rajya Sabha Representation**: Allocation of seats for states and union territories
- **State Representation**: 233 total seats distributed among states
- **Union Territory Representation**: Delhi (3), Puducherry (1), Jammu & Kashmir (4)

### Fifth Schedule (Article 244(1))
- **Scheduled Areas**: Special administrative provisions for tribal areas
- **Governor's Powers**: Executive authority over scheduled areas
- **Tribes Advisory Council**: Advisory body with up to 20 members
- **Regulatory Powers**: Governor's authority to make regulations for tribal welfare

### Sixth Schedule (Articles 244(2) and 275(1))
- **Autonomous Districts**: Self-governing tribal areas in northeastern states
- **District Councils**: Maximum 30 members with administrative powers
- **Regional Councils**: Separate councils for autonomous regions
- **Tribal Justice System**: Village courts and appeal mechanisms

## Constitutional Significance

This framework establishes:

1. **Federal Representation**: Ensures proportional representation of states and UTs in Rajya Sabha
2. **Tribal Protection**: Special administrative arrangements for scheduled tribes
3. **Autonomous Governance**: Self-governance for tribal areas in northeastern states
4. **Judicial Hierarchy**: Specialized court system for tribal areas
5. **Cultural Preservation**: Protection of tribal customs, laws, and traditions

The structure balances national integration with tribal autonomy, ensuring constitutional protection for indigenous communities while maintaining judicial oversight through the higher courts.