# Sheet Metal Projects — SolidWorks

> A curated collection of sheet-metal parts, assemblies, and manufacturing-ready outputs created in SolidWorks.  

> Focus: clean, parametric models; flat patterns; DXF exports; and fabrication-ready documentation.



---

# About

This repository contains sheet-metal models designed with real-world manufacturability in mind. Each part is modeled parametricly to allow easy dimension tweaks and quick generation of flat patterns and DXF drawings for laser cutting, CNC bending, and production.

Files are provided as:

- SolidWorks part files (`.SLDPRT`) — both folded (3D) and flat pattern versions

- DXF/STEP exports for manufacturing

- Rendered previews and exploded views

- Optional manufacturing notes & bend tables



---

# Conventions & Units

- **Units:** Millimetres (mmgs) — all files use mm unless otherwise noted.  

- **Material:** Specify material in part file (e.g., 1.2 mm SPCC, 304 SS 1.0 mm) — see `manufacturing/notes.md`.  

- **Bend Allowance:** Keep a column for K-factor / bend allowance in `manufacturing/bend_table.csv` for each part.





# Style & Modeling rules
- Model sheet-metal parts using the **Sheet Metal** feature set (Base Flange, Edge Flange, Hem, Lofted Flange, etc.).
  
- Keep sketches fully constrained and use named dimensions for easy parameter changes.  

- Use configurations to store different thicknesses or material variants.  

- Avoid importing raster images as sketches for profile geometry — use true splines or sketch entities for accuracy.

---

---

# License
This repository is released under the **MIT License** — see `LICENSE` for details.

-
---
