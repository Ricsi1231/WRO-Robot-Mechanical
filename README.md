# WRO-Robot-Mechanical - TEAM TRAKTORISTAK

> Mechanical design repository for the WRO Future Engineers 2026 autonomous vehicle. Contains the CAD assemblies and 3D-printable model files used to build the robot chassis and mounting structure.

## Team Members (Mechanical)

| Role | Member | Responsibilities |
|------|--------|------------------|
| CAD Design Leader | **Predrag Prijovic** | CAD Design, Mechanical Engineering, Robot Assembly |
| Mechanical Design Support | **Mark Gulyas** | Assistance, Part Development, Robot Assembly |

## Content Structure

- `kocsi.stp` - Full robot CAD assembly in STEP format. Use this file to open, edit, and modify the design in CAD software (Fusion 360, SolidWorks, FreeCAD, etc.).
- `kocsi.stl` - Mesh export of the robot assembly in STL format, ready for 3D-printing and slicer software.
- `LICENSE` - Repository license.

## File Formats

- **STEP (`.stp`)** - Parametric CAD exchange format. Preserves part geometry and assembly structure, suitable for further engineering modifications.
- **STL (`.stl`)** - Triangulated mesh format. Used for 3D-printing the chassis and mechanical components.

## Usage

To view or edit the CAD model, open `kocsi.stp` in any STEP-compatible CAD tool. To 3D-print the chassis, load `kocsi.stl` into your preferred slicer (Cura, PrusaSlicer, Bambu Studio, etc.) and generate the printer-ready G-code.

## Related Repositories

This repository is a submodule of the main WRO-Robot project:

- [WRO-Robot](https://github.com/Ricsi1231/WRO-Robot) - Main project repository and documentation
- [WRO-Robot-Hardware](https://github.com/Ricsi1231/WRO-Robot-Hardware) - Electronics, schematics, and wiring
- [WRO-Robot-Software](https://github.com/Ricsi1231/WRO-Robot-Software) - Robot control source code
