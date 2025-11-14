---
title: EmfMapMode Enumeration
type: docs
weight: 210
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

The MapMode enumeration is used to define the unit of measure for transforming page <br/>            space units into device space units and for defining the orientation of the drawing axes.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| MM_ANISOTROPIC | Logical units are mapped to arbitrary units with arbitrarily scaled axes. <br/>            The EMR_SETWINDOWEXTEX and EMR_SETVIEWPORTEXTEX records SHOULD be used to specify the units, <br/>            orientation, and scaling. |
| MM_HIENGLISH | Each logical unit is mapped to 0.001 inch. Positive x is to the right; positive y is up. |
| MM_HIMETRIC | Each logical unit is mapped to 0.01 millimeter. Positive x is to the right; positive y is up. |
| MM_ISOTROPIC | Logical units are mapped to arbitrary units with equally scaled axes; that is, one unit <br/>            along the x-axis is equal to one unit along the y-axis. The EMR_SETWINDOWEXTEX and <br/>            EMR_SETVIEWPORTEXTEX records SHOULD be used to specify the units and the orientation <br/>            of the axes.<br/>            Adjustments MUST be made as necessary to ensure that the x and y units remain the same size. <br/>            For example, when the window extent is set, the viewport MUST be adjusted to keep the units isotropic. |
| MM_LOENGLISH | Each logical unit is mapped to 0.01 inch. Positive x is to the right; positive y is up |
| MM_LOMETRIC | Each logical unit is mapped to 0.1 millimeter. Positive x is to the right; positive y is up. |
| MM_TEXT | Each logical unit is mapped to one device pixel. Positive x is to the right; positive y is down. |
| MM_TWIPS | Each logical unit is mapped to one-twentieth of a printer's point <br/>            (1/1440 inch, also called a "twip"). Positive x is to the right; positive y is up. |
