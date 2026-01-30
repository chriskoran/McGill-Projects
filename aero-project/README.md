# Aircraft Electrification Case Study — AA-1 Yankee Clipper  
*AERO 401, Fall 2025*

**Final report (PDF):** `report/AeroProjectReport.pdf`

---

## Overview
This project evaluates a **pure-electric conversion** of the American Aviation **AA-1 Yankee Clipper**, focusing on:

- electric powertrain selection and integration  
- weight and balance/stability impacts  
- engine mount design and **FAR 23 load-case analysis**  
- mission-level performance estimation  
- avionics and electrical system redesign for high- and low-voltage subsystems  

---

## Team
Chris Koran, Amelia Loch, Elie Mouterde, Rawan Olabi

---

## Technical summary

### Configuration choices
- Target aircraft: **AA-1 Yankee Clipper**, with electrification constrained to preserve baseline performance where feasible  
- Motor selection scoped to **MGM COMPRO** motors, shortlisted based on power, RPM, and integration feasibility  

### Structures: engine mount (FEA)
- Engine mount modeled in **Abaqus** as a truss/wireframe structure  
- Material: **Ti-6Al-4V (Grade 5)** selected for high strength-to-weight ratio  
- **FAR-informed load cases** (inertial, torque, lateral, and gyroscopic) applied with a **1.5 safety factor**  

### Performance (mission-level)
Under the report’s stated conservative assumptions:

- Cruise segment: approximately **11 minutes** and **~21.5 NM** beyond top-of-climb  
- Total time aloft: **42.9 minutes**  
- Total mission range: **~75.75 NM** (≈ **87.17 miles**)  

---

## Key conclusion
A fully electric propulsion system is mechanically and integration-feasible at a project level; however, the report finds **substantially reduced performance relative to the fuel-powered baseline**, driven primarily by battery mass and current battery energy-density limitations. Hybrid-electric architectures are identified as a more practical near-term alternative.
