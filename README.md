<!-- Reference-style links to make tables & lists more readable -->
[OpenOffice]: https://www.openoffice.org/
[LibreOffice]: https://www.libreoffice.org/discover/libreoffice/


# ElectricalDiagrams: Publication-quality circuit schematics

## Description

This repository provides symbol libraries to generate electrical/electronic circuit schematics. The libraries are stored in simple .odg (Open Document Graphic) files, which are compatible with programs supporting the Open Document Format (ODF) standard (ex: [OpenOffice], [LibreOffice]).

## Libraries

### [Symbols\_Electrical.odg](Symbols_Electrical.odg)

<img src="img/Symbols_Electrical.png">

## Suggested Configuration

### LibreOffice 4.2

To ease the process of positionning & connecting schematic symbols, it is highly suggested you modify the grid settings by following these steps:

 1. Create a new drawing.
 1. In `Tools|Options...|LibreOffice Draw|General`:
    - Set `Unit of measurement` = `Millimeter`.

 1. In `Tools|Options...|LibreOffice Draw|Grid`:
    - Select `Snap to grid` & `Visible grid`.
    - Set `Resolution` (H&V) = 10mm (coarse resolution).
    - Set `Subdivision` (H&V) = 5 (Target: 2mm fine resolution).
    - `Snap` &rArr; Select nothing.
    - `Snap position` &rArr; Only check `When rotating` - set to 90deg.

 1. In Format|Styles and Formatting:
    - Right-click on `Default` & click on `Modify`.
    - Set `Width` = 1mm.
