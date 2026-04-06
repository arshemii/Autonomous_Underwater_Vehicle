# AUV Pipeline Inspection Concept Design

This repository contains my university concept-design project for an autonomous underwater vehicle (AUV) intended for underwater pipeline inspection.

The work focuse son system development: requirements, architectures, basic verification, and a CAD concept of the vehicle. The main tools used were Visual Paradigm, MATLAB System Composer / Simulink, and SolidWorks.

## CAD preview

![AUV CAD preview](assets/cad_screenshots/iso_view.jpg)

## What is inside

- **Requirements** for mission, communication, perception, localization, diagnosis, control, safety, and maintenance
- **Architecture models** created in Visual Paradigm and MATLAB System Composer / Simulink
- **Test-related models and test artifacts** for selected system functions
- **SolidWorks CAD files** for the AUV concept and its main parts
- **CAD screenshots** for quick viewing on GitHub

## Repository structure

```text
assets/
  cad_screenshots/              CAD renders from the basic prototype
  architecture_screenshots/     Architectures from Visual Paradigm

mbse/
  matlab_simulink/              System Composer, Simulink, requirements, and test files

visual_paradigm/
  AUV.vpp                       The main Visual Paradigm project

cad/
  solidworks/                   SolidWorks assembly and part files
```

## Main files

### MATLAB / Simulink / System Composer
- `mbse/matlab_simulink/AUVreq.slreqx`
- `mbse/matlab_simulink/DiagnosPipeline.slx`
- `mbse/matlab_simulink/DiagnosPipelineLogical.slx`
- `mbse/matlab_simulink/Controller.slx`
- `mbse/matlab_simulink/IntegratedLocalizationProcessor.slx`
- `mbse/matlab_simulink/DiagnosisProcessor.slx`
- `mbse/matlab_simulink/NavigationProcessor.slx`
- `mbse/matlab_simulink/SysForTest.slx`

### Visual Paradigm
- `visual_paradigm/AUV.vpp`

### SolidWorks
- `cad/solidworks/Assem1.SLDASM`

## Architecture screenshots

```md
## Architecture snapshots

![Activity Diagram](assets/architecture_screenshots/Activity Diagram.png)
![Block Definition Diagram](assets/architecture_screenshots/Block Definition Diagram.png)
![Block Definition Diagram (White box)](assets/architecture_screenshots/Block Definition Diagram (White box).png)
![Internal Block Diagram](assets/architecture_screenshots/Internal Block Diagram.png)
![Internal Block Diagram (White box)](assets/architecture_screenshots/Internal Block Diagram (White box).png)
![Life Cycle](assets/architecture_screenshots/Life Cycle.png)
![Requirement Diagram](assets/architecture_screenshots/Requirement_Diagram.png)
![Sequence Diagram](assets/architecture_screenshots/Sequence Diagram.png)
![Use Case Diagram](assets/architecture_screenshots/Use Case Diagram.png)
![User Operating Mode](assets/architecture_screenshots/User Operating Mode.png)
```
## CAD preview

![Requirement Tree](assets/architecture_screenshots/Requirement_Diagram.png)

## Notes

This is a concept and system-design project, so the repository is centered on requirements, architecture, verification models, and CAD rather than implementation-level embedded software.

Generated cache folders, backup files, and temporary MATLAB artifacts were removed to keep the repository cleaner.
