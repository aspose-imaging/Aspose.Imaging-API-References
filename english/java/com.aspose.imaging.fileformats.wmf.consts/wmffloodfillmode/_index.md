---
title: WmfFloodFillMode
second_title: Aspose.Imaging for Java API Reference
description: The FloodFill Enumeration specifies the type of fill operation to be performed.
type: docs
weight: 18
url: /java/com.aspose.imaging.fileformats.wmf.consts/wmffloodfillmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFloodFillMode extends System.Enum
```

The FloodFill Enumeration specifies the type of fill operation to be performed.
## Fields

| Field | Description |
| --- | --- |
| [FloodFillBorder](#FloodFillBorder) | The fill area is bounded by the color specified by the Color member. |
| [FloodFillSurface](#FloodFillSurface) | The fill area is bounded by the color that is specified by the Color member. |
### FloodFillBorder {#FloodFillBorder}
```
public static final int FloodFillBorder
```


The fill area is bounded by the color specified by the Color member. This style is identical to the filling performed by the META\_FLOODFILL record.

### FloodFillSurface {#FloodFillSurface}
```
public static final int FloodFillSurface
```


The fill area is bounded by the color that is specified by the Color member. Filling continues outward in all directions as long as the color is encountered. This style is useful for filling areas with multicolored boundaries.

