# Basis of Design (BoD) – v0.1

## 1. Project Overview
**Project type:** Industrial manufacturing building  
**Location:** Belgium  
**Design stage:** Concept / early design  
**Objective:** Define HVAC and building-services design principles based on limited client input, aligned with Belgian / EU practice.

---

## 2. Client Inputs (Given)
The client has provided the following high-level information:
- Building function: Industrial manufacturing facility
- Approximate floor area: [to be defined]
- Operating hours: [e.g. 8–16, 5 days/week]
- Process requirement: [general manufacturing / clean process area]
- Special areas:
  - Cleanroom-like space (process-driven)
  - Office/support spaces

No detailed HVAC requirements were provided by the client.

---

## 3. Design Assumptions (By Engineer)
Due to limited client input, the following assumptions are made:
- HVAC systems will be designed to meet process and comfort needs
- EU units will be used consistently (kW, m³/h, °C)
- Cleanroom classification and validation are by others
- Vendor-specific equipment selection is out of scope at this stage
- EPB compliance will be considered at concept level only

These assumptions will be reviewed during later design stages.

---

## 4. Zoning Philosophy
The building is divided into HVAC zones based on usage:
- Industrial hall (general production)
- Cleanroom-like process area
- Offices
- Meeting rooms
- Storage / technical spaces

Each zone will be served based on its specific airflow, filtration, and pressure requirements.

---

## 5. Indoor Design Conditions
| Zone | Temperature | Relative Humidity | Notes |
|----|----|----|----|
| Industrial hall | [e.g. 18–26 °C] | [e.g. not controlled] | Comfort/process dependent |
| Cleanroom-like area | [e.g. 20–22 °C] | [e.g. 45–55 %] | Process-driven |
| Offices | 20–24 °C | 40–60 % | Comfort |
| Meeting rooms | 20–24 °C | 40–60 % | Comfort |

---

## 6. Ventilation & Airflow Strategy
- Ventilation rates will be determined based on:
  - Occupancy
  - Process requirements
  - Space function
- Airflow units: m³/h
- Cleanroom-like areas will be designed with:
  - High air change rates
  - Pressure control relative to adjacent spaces
  - High-efficiency filtration

---

## 7. Air Handling Unit (AHU) Design Principles
AHUs will generally consist of:
- Outdoor air intake
- Return / exhaust air paths (where permitted)
- Filtration stages (pre-filters, fine filters, HEPA where required)
- Heating and cooling coils
- Supply and return fans
- Heat recovery where applicable

System type (one-through vs recirculation) will be selected per zone based on contamination risk and process needs.

---

## 8. Heating & Cooling Generation (Concept)
- Cooling will be provided by:
  - Central chilled water system (preferred for industrial applications)
  - DX systems considered only for small or isolated loads
- Heating will be provided by:
  - Heat pumps as primary source
  - Fossil fuel boilers are not considered at concept stage

---

## 9. Refrigeration & F-gas Awareness
- Refrigeration systems must comply with EU F-gas regulations
- Preference for low-GWP refrigerants
- Refrigerant selection is vendor responsibility, but system choice must consider regulatory constraints

---

## 10. Utilities & Interfaces (Awareness)
The following utilities may interface with HVAC systems:
- Chilled water (generation & distribution)
- Heating water
- Steam (e.g. humidification)
- Compressed air (process utility)
- Condensate drainage
- Sanitary systems (above ground)

Detailed design of these systems is outside current scope.

---

## 11. Fire Protection (High-Level Only)
Fire protection systems (sprinklers, gas systems, etc.) are designed by specialist contractors.
HVAC design will account for:
- Fire compartmentation
- Smoke control interfaces
- Equipment room zoning

---

## 12. Scope Boundaries
**Included:**
- HVAC design principles
- Concept-level calculations
- System schematics
- BIM layout and coordination intent

**Excluded:**
- Detailed pipe sizing
- Certified fire system design
- Cold room detailed design
- EPB certification documentation

---

## 13. Next Design Steps
- Define building geometry and zones
- Calculate ventilation airflows
- Estimate heating and cooling loads
- Develop AHU schematics
- Begin BIM layout (Revit)
