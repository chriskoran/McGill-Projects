# Aircraft Electrification Case Study — AA-1 Yankee Clipper (AERO 401, Fall 2025)

**Final report (PDF):** `report/AeroProjectReport.pdf` :contentReference[oaicite:0]{index=0}

## Overview
This project evaluates a **pure-electric conversion** of the **American Aviation AA-1 Yankee Clipper**, focusing on:
- electric powertrain selection and integration
- weight & balance / stability impacts
- **engine mount design + FAR 23 load-case analysis**
- mission-level performance estimation
- avionics/electrical system redesign for high- and low-voltage subsystems :contentReference[oaicite:1]{index=1}

## Team
Group 7 — Chris Koran, Amelia Loch, Elie Mouterde, Rawan Olabi :contentReference[oaicite:2]{index=2}

## Technical summary (high level)
### Configuration choices
- Target aircraft: AA-1 Yankee Clipper; electrification to match original performance constraints where possible :contentReference[oaicite:3]{index=3}
- Motor selection process scoped to **MGM COMPRO** motors; shortlist based on power/RPM and feasibility constraints :contentReference[oaicite:4]{index=4}

### Structures: engine mount (FEA)
- Engine mount modeled in **Abaqus** as a truss/wireframe structure
- Material: **Ti-6Al-4V (Grade 5)** selected for strength-to-weight; key properties tabulated in report :contentReference[oaicite:5]{index=5}
- FAR-informed load cases (inertial + torque + lateral + gyroscopic) with **1.5 safety factor** applied :contentReference[oaicite:6]{index=6}

### Performance (mission-level)
Under the report’s stated conservative assumptions:
- Cruise segment: ~**11 minutes** and ~**21.5 NM** cruise range beyond top-of-climb :contentReference[oaicite:7]{index=7}
- Total time aloft: **42.9 minutes**
- Total mission range: **~75.75 NM** (≈87.17 miles) :contentReference[oaicite:8]{index=8}

## Key conclusion
A fully electric propulsion system is mechanically/integration-feasible at a project level, but the report finds **substantially reduced performance vs. the fuel baseline**, primarily due to battery weight and today’s battery energy density constraints; hybrid architectures are highlighted as a more practical near-term direction. :contentReference[oaicite:9]{index=9}

## Repository layout
