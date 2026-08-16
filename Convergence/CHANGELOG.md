# Changelog

All notable changes to **Convergence** are documented in this file.

The project follows the version declared in `package.xml`.

## [1.0.0](https://github.com/difrkaguilar/Convergence/releases/tag/v1.0.0) - Initial Release

### Added

-   Initial release of the Convergence FreeCAD Preference Pack.
-   Professional dark Qt interface styling.
-   Custom main FreeCAD stylesheet (`Convergence.qss`).
-   Custom FreeCAD overlay stylesheet (`Convergence-overlay.qss`).
-   Custom viewport background based on `#636B72`.
-   Default shape color configured to `#808080FF`.
-   Default shape line width configured to `4.00`.
-   Neutral viewport lighting configured to `#DCDCDCFF` for:
    -   Main/headlight.
    -   Backlight.
    -   Fill light.
    -   Ambient light.
-   Customized Sketcher appearance.
-   Customized Sketcher geometry colors.
-   Customized Sketcher constraint colors.
-   Customized constraint icon color.
-   Customized driving/constrained dimension color.
-   Customized non-driving/reference dimension color.
-   Customized expression-based constraint dimension color.
-   Customized deactivated constraint dimension color.
-   Customized fully constrained geometry colors.
-   Customized construction geometry color.
-   Customized external geometry color.
-   Customized invalid Sketch color.
-   Customized Sketch cursor and crosshair colors.
-   Customized Draft grid, snap, and construction colors.
-   Customized Arch colors for walls, structures, rebar, windows, glass,
    panels, helpers, and spaces.
-   Customized Spreadsheet colors for text, aliased cells, positive
    values, and negative values.
-   Customized Start page colors.
-   Customized TechDraw background color.
-   Customized Output Window colors.
-   Customized Python/editor syntax colors.
-   Customized Tree View colors.
-   FreeCAD overlay panel styling.
-   FreeCAD property editor styling.
-   Dark toolbar, menu, tab, button, input, tree, list, table, and
    dialog styling.
-   Preference Pack metadata and MIT licensing information.

### Design

-   Established a neutral blue-gray viewport instead of a pure black
    viewport.
-   Established a neutral gray default shape appearance.
-   Established a neutral light-gray lighting setup.
-   Introduced a restrained professional dark UI palette.
-   Designed the interface to prioritize technical readability and
    long-session usability.
-   Established a consistent visual language between FreeCAD's desktop
    interface, overlays, Sketcher, and 3D viewport.

### Development Notes

-   The theme uses FreeCAD preference parameters for visual properties
    that cannot be controlled reliably through QSS.
-   The project uses `Convergence.cfg` as the source of truth for
    persistent FreeCAD visual preferences.
-   The project uses `Convergence.qss` for the primary Qt interface.
-   The project uses `Convergence-overlay.qss` for FreeCAD overlay
    styling.
-   The theme was developed and tested against FreeCAD 1.1.3.
-   Reapplying the Preference Pack is required when testing changes made
    to `Convergence.cfg`, because FreeCAD persists previously applied
    preference values in its user configuration.

### Known Limitations

-   Some 3D selection and preselection effects are controlled by
    FreeCAD's internal rendering/selection system rather than by Qt
    stylesheet rules.
-   Visual behavior can therefore differ between ordinary viewport
    colors and selection/preselection overlays.
-   Compatibility with FreeCAD versions other than the tested version is
    not guaranteed.

------------------------------------------------------------------------

## Unreleased

### Planned

-   Further refinement of Sketcher constraint and dimensional colors.
-   Further refinement of selection and preselection rendering.
-   Additional testing across FreeCAD workbenches.
-   Compatibility testing against future FreeCAD releases.
-   Additional documentation of FreeCAD-specific visual parameters.
