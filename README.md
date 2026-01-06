## Deed Plotter
A browser-based Deed Plotter that converts metes-and-bounds deed descriptions into accurate geodesic geometry, with optional RTK-based site localization and practical export options for analysis and visualization.

The tool parses deed calls (lines and curves), computes true geodesic points (no flat-earth assumptions), and supports workflows commonly used in boundary retracement and legacy plat reconstruction. RTK points can be supplied at the ending point of a deed call, allowing the parcel to be translated and rotated into real-world position without distorting the deed geometry.

Key features include:

- Metes & bounds parsing (lines + curves)

- True/geodesic point computation

- Optional RTK localization (translation + rotation, with optional scale solve)

- Automatic handling when no POB is provided (deed call reordering)

- Canvas-based plotting with bearing-aligned, multiline labels

- Residual distance reporting at RTK control points

- KML export for direct visualization and retracement in SWMaps

- CSV export of computed calls, coordinates, and residuals

- The entire plotting and computation workflow runs client-side in the browser, making it easy to experiment with deed geometry, RTK control, and legacy plats without specialized CAD or GIS software.

Demo: https://845.ddns.net/deed-plotter.html

## Disclosure / Disclaimer

I am not a licensed professional surveyor and not a mathematician. I am a hobbyist with an interest in land records, mapping, and geometry, and this tool was created for personal exploration and educational purposes while researching my own property corners.

This tool is not intended to provide survey-grade results, legal boundary determinations, or authoritative measurements. To the best of my knowledge, the outputs produced by this tool should not be relied upon for legal, engineering, construction, or land-use decisions.

Any results generated are approximate, dependent on the accuracy of input data (deed descriptions, RTK points, assumptions, etc.), and may differ from the findings of a licensed professional surveyor using certified equipment and methodologies.

If you require legally defensible boundary information or precise positioning, you should consult a licensed land surveyor.
