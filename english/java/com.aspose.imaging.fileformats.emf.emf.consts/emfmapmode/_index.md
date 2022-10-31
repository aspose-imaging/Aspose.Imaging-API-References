---
title: EmfMapMode
second_title: Aspose.Imaging for Java API Reference
description: The MapMode enumeration is used to define the unit of measure for transforming page space units into device space units and for defining the orientation of the drawing axes.
type: docs
weight: 30
url: /java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

The MapMode enumeration is used to define the unit of measure for transforming page space units into device space units and for defining the orientation of the drawing axes.
## Fields

| Field | Description |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Each logical unit is mapped to one device pixel. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Each logical unit is mapped to 0.1 millimeter. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Each logical unit is mapped to 0.01 millimeter. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Each logical unit is mapped to 0.01 inch. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Each logical unit is mapped to 0.001 inch. |
| [MM_TWIPS](#MM-TWIPS) | Each logical unit is mapped to one-twentieth of a printer's point (1/1440 inch, also called a "twip"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Logical units are mapped to arbitrary units with equally scaled axes; that is, one unit along the x-axis is equal to one unit along the y-axis. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Logical units are mapped to arbitrary units with arbitrarily scaled axes. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Each logical unit is mapped to one device pixel. Positive x is to the right; positive y is down.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Each logical unit is mapped to 0.1 millimeter. Positive x is to the right; positive y is up.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Each logical unit is mapped to 0.01 millimeter. Positive x is to the right; positive y is up.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Each logical unit is mapped to 0.01 inch. Positive x is to the right; positive y is up

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Each logical unit is mapped to 0.001 inch. Positive x is to the right; positive y is up.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Each logical unit is mapped to one-twentieth of a printer's point (1/1440 inch, also called a "twip"). Positive x is to the right; positive y is up.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Logical units are mapped to arbitrary units with equally scaled axes; that is, one unit along the x-axis is equal to one unit along the y-axis. The EMR\_SETWINDOWEXTEX and EMR\_SETVIEWPORTEXTEX records SHOULD be used to specify the units and the orientation of the axes. Adjustments MUST be made as necessary to ensure that the x and y units remain the same size. For example, when the window extent is set, the viewport MUST be adjusted to keep the units isotropic.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Logical units are mapped to arbitrary units with arbitrarily scaled axes. The EMR\_SETWINDOWEXTEX and EMR\_SETVIEWPORTEXTEX records SHOULD be used to specify the units, orientation, and scaling.

