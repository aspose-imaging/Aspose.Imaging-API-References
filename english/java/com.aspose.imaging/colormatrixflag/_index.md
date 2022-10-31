---
title: ColorMatrixFlag
second_title: Aspose.Imaging for Java API Reference
description: Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an .
type: docs
weight: 27
url: /java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | All color values, including gray shades, are adjusted by the same color-adjustment matrix. |
| [SkipGrays](#SkipGrays) | All colors are adjusted, but gray shades are not adjusted. |
| [AltGrays](#AltGrays) | Only gray shades are adjusted. |
### Default {#Default}
```
public static final int Default
```


All color values, including gray shades, are adjusted by the same color-adjustment matrix.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


All colors are adjusted, but gray shades are not adjusted. A gray shade is any color that has the same value for its red, green, and blue components.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Only gray shades are adjusted.

