# 3D-print-samples
Samples for 3D printers as references.

## Quick Start
- Use the _.print_ files to print directly, or
- Import stl files _as assembly_, set up the 3D printer, then print.

## Connex3 Objet260 3D Printer [[specs](https://www.stratasys.com/3d-printers/objet260-connex3)]

### Tray materials
- [VeroWhitePlus](https://www.stratasys.com/materials/search/vero): General purpose, high dimensional stability, e-Modulus, 2000-3000 MPa, HDT 45-50&deg;C, white.
- [VeroClear](https://www.stratasys.com/materials/search/veroclear): General purpose, HDT 49&deg;C, clear.
- [Agilus30Black](https://www.stratasys.com/materials/search/agilus30): Rubber-like, Shore A30, Elongation at break 250%, good tear resistance. 

### Digital materials [[datasheet](./res/MSS_PJ_DigitalMaterialsDataSheet_0617a.pdf)]
- VeroWhitePlus + VeroClear: Rigid, different opacities.
  - RGD-WT-001-DM: Almost opque. 
  - ...
  - RGD-WT-007-DM: Almost transparent. 
- VeroWhitePlus + Agilus30Black: Different rigidity / flexibility.
  - RGDA8505-DM: High rigidity, impact 25 J/m, Elongation at break 15% ~ 25%. 
  - RGDA8510-DM: (The same property as RGDA8505-DM, darker color.)
  - RGDA8515-DM: (The same property as RGDA8505-DM, darker color.)
  - RGDA8520-DM: (The same property as RGDA8505-DM, darker color.)
  - RGDA8525-DM: High rigidity, impact 25 J/m, Elongation at break 20% ~ 30%.
  - RGDA8530-DM: High rigidity, impact 30 J/m, Elongation at break 25% ~ 35%.
  - FLXA9840-DM: Rubber-like, Shore A40.
  - FLXA9850-DM: Rubber-like, Shore A50.
  - FLXA9860-DM: Rubber-like, Shore A60.
  - FLXA9870-DM: Rubber-like, Shore A70.
  - FLXA9885-DM: Rubber-like, Shore A85.
  - FLXA9895-DM: Rubber-like, Shore A95.
- VeroClear + Agilus30Black: The same as VeroWhitePlus + Agilus30Black, with different opacities for rigid materials. 
  - RGDA8705-DM ~ RGDA8730-DM: High rigidity, from transparent to translucent.
  - FLXA9040-DM ~ FLXA9095-DM: Rubber-like, opaque. 
