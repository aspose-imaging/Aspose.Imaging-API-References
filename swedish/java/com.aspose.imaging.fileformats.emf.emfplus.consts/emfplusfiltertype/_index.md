---
title: "EmfPlusFilterType"
second_title: "Aspose.Imaging för Java API-referens"
description: "FilterType‑enumerationen definierar typer av filtreringsalgoritmer som kan användas för förbättring av text- och grafik kvalitet samt bildrendering."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

FilterType‑enumerationen definierar typer av filtreringsalgoritmer som kan användas för förbättring av text- och grafik kvalitet samt bildrendering.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Specificerar att filtrering inte utförs. |
| [FilterTypePoint](#FilterTypePoint) | Specificerar att varje destinationspixel beräknas genom att sampla den närmaste pixeln från källbilden. |
| [FilterTypeLinear](#FilterTypeLinear) | Specificerar att linjär interpolation utförs med det viktade genomsnittet av ett 2x2‑område av pixlar kring källpixeln. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Specificerar att varje pixel i källbilden bidrar lika till destinationsbilden. |
| [FilterTypeBox](#FilterTypeBox) | Specificerar en boxfilter‑algoritm, där varje destinationspixel beräknas genom att medelvärdesbilda en rektangel av källpixlar. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Specificerar att ett 4‑samples tältfilter används. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Specificerar att ett 4‑samples Gaussfilter används, vilket skapar en oskärpeeffekt på en bild. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Specificerar att filtrering inte utförs.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Specificerar att varje destinationspixel beräknas genom att sampla den närmaste pixeln från källbilden.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Specificerar att linjär interpolation utförs med det viktade genomsnittet av ett 2x2‑område av pixlar kring källpixeln.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Specificerar att varje pixel i källbilden bidrar lika till destinationsbilden. Detta är den långsammaste av filtreringsalgoritmerna.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Anger en boxfilteralgoritm där varje destinationspixel beräknas genom att medelvärdesbilda en rektangel av källpixlar. Denna algoritm är endast användbar när bildens storlek minskas.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Specificerar att ett 4‑samples tältfilter används.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Specificerar att ett 4‑samples Gaussfilter används, vilket skapar en oskärpeeffekt på en bild.

