---
title: Enum EmfMapMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfMapMode enum. The MapMode enumeration is used to define the unit of measure for transforming page space units into device space units and for defining the orientation of the drawing axes
type: docs
weight: 2830
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
## EmfMapMode enumeration

The MapMode enumeration is used to define the unit of measure for transforming page space units into device space units and for defining the orientation of the drawing axes.

```csharp
public enum EmfMapMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MM_TEXT | `1` | Each logical unit is mapped to one device pixel. Positive x is to the right; positive y is down. |
| MM_LOMETRIC | `2` | Each logical unit is mapped to 0.1 millimeter. Positive x is to the right; positive y is up. |
| MM_HIMETRIC | `3` | Each logical unit is mapped to 0.01 millimeter. Positive x is to the right; positive y is up. |
| MM_LOENGLISH | `4` | Each logical unit is mapped to 0.01 inch. Positive x is to the right; positive y is up |
| MM_HIENGLISH | `5` | Each logical unit is mapped to 0.001 inch. Positive x is to the right; positive y is up. |
| MM_TWIPS | `6` | Each logical unit is mapped to one-twentieth of a printer's point (1/1440 inch, also called a "twip"). Positive x is to the right; positive y is up. |
| MM_ISOTROPIC | `7` | Logical units are mapped to arbitrary units with equally scaled axes; that is, one unit along the x-axis is equal to one unit along the y-axis. The EMR_SETWINDOWEXTEX and EMR_SETVIEWPORTEXTEX records SHOULD be used to specify the units and the orientation of the axes. Adjustments MUST be made as necessary to ensure that the x and y units remain the same size. For example, when the window extent is set, the viewport MUST be adjusted to keep the units isotropic. |
| MM_ANISOTROPIC | `8` | Logical units are mapped to arbitrary units with arbitrarily scaled axes. The EMR_SETWINDOWEXTEX and EMR_SETVIEWPORTEXTEX records SHOULD be used to specify the units, orientation, and scaling. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


