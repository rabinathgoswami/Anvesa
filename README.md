# ANVESHAK — Low-Cost Deployable Seafloor Metal Detection Sensor

> **Smart India Hackathon 2026 | Problem Statement: SIH 26064**  
> **Theme:** Robotics and Drones  
> **Category:** Hardware  
> **Organization:** Ministry of Earth Sciences (MoES)  
> **Department:** National Centre for Polar and Ocean Research (NCPOR)

## Overview

**ANVESHAK** is a proposed low-cost, deployable seafloor sensing platform for preliminary deep-ocean mineral exploration. The system is designed around a **modular sensing architecture** rather than a conventional autonomous underwater vehicle (AUV) or remotely operated vehicle (ROV).

The core idea is to deploy multiple compact sensing modules from a research vessel, allow them to descend to the seafloor, collect synchronized measurements, store the data locally, and recover the modules after the survey.

The system combines **magnetic, acoustic, and controlled-source electromagnetic (CSEM)** sensing with pressure, temperature, and inertial measurements. These complementary measurements are intended to identify **spatial anomalies and mineral-prospectivity patterns**, rather than directly determine the exact elemental composition of a deposit.

## Current Status

The project is currently in the **concept development and pre-prototyping stage**.

- Gathering technical knowledge and studying relevant research literature.
- Building software-based models and simulations for the proposed system.
- Developing the mechanical and electronic system concepts.
- Investigating suitable materials for the deep-sea pressure housing and other components.
- Identifying practical fabrication and manufacturing sources.
- Estimating the budget required for prototype development and testing.

## Repository / Project Structure

The project files are organized as follows:

```text
SIH/
├── README.md
├── REPORT FILES/
│   ├── BACKGROUND STUDY/
│   ├── BUDGET/
│   ├── ELECTRICAL SUBSYSTEM/
│   ├── FABRICATION APPROACHES/
│   ├── MECHANICAL SUBSYSTEM/
│   ├── OTHER/
│   └── SOFTWARE/
├── REFERENCES/
│   └── Research papers and supporting literature
├── Archives/
│   └── Old drafts and previous versions
├── SIH_Report.pdf
└── SIH_Report.zip
```

### `REPORT FILES/`

Contains the working material used to develop and support the main report.

- **BACKGROUND STUDY/** — Background research, technical notes, and supporting studies.
- **BUDGET/** — Cost estimates, component pricing, and prototype budget calculations.
- **ELECTRICAL SUBSYSTEM/** — Electronics, sensors, PCB, power, and related electrical-system work.
- **FABRICATION APPROACHES/** — Manufacturing methods, fabrication options, and possible fabrication sources.
- **MECHANICAL SUBSYSTEM/** — Mechanical design, CAD models, pressure housing, structural design, and related work.
- **OTHER/** — Miscellaneous project material that does not fit into the other categories.
- **SOFTWARE/** — Software models, simulations, algorithms, data processing, and related development.

### `REFERENCES/`

Contains research papers, technical reports, and supporting literature used for the project and report preparation.

### `Archives/`

Contains old drafts, previous versions, and material retained for reference. These files are not part of the current active development unless specifically required.

### `SIH_Report.pdf`

This is the **PDF version of the project report prepared for submission/email communication**.

### `SIH_Report.zip`

This ZIP contains the **main LaTeX/Overleaf report source**, including the `.tex` file and associated report assets.

To edit the main report:

1. Upload `SIH_Report.zip` to Overleaf.
2. Edit and compile the report in Overleaf.
3. Export the updated PDF.
4. Update/export the ZIP containing the latest report source.
5. Submit a pull request containing **both the updated PDF and updated ZIP**.

The PDF and ZIP should correspond to the **same report version**.

## Project Documentation Workflow

The repository should keep the active report, supporting material, references, and older drafts separated. New research or development work should be placed in the appropriate `REPORT FILES/` subfolder, while finalized report changes should be reflected in both `SIH_Report.pdf` and `SIH_Report.zip`.
