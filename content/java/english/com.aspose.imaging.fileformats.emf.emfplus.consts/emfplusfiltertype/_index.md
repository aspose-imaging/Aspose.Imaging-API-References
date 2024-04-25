---
title: EmfPlusFilterType
second_title: Aspose.Imaging for Java API Reference
description: The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering.
type: docs
weight: 22
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering.
## Fields

| Field | Description |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Specifies that filtering is not performed. |
| [FilterTypePoint](#FilterTypePoint) | Specifies that each destination pixel is computed by sampling the nearest pixel from the source image. |
| [FilterTypeLinear](#FilterTypeLinear) | Specifies that linear interpolation is performed using the weighted average of a 2x2 area of pixels surrounding the source pixel. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Specifies that each pixel in the source image contributes equally to the destination image. |
| [FilterTypeBox](#FilterTypeBox) | Specifies a box filter algorithm, in which each destination pixel is computed by averaging a rectangle of source pixels. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Specifies that a 4-sample tent filter is used. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Specifies that a 4-sample Gaussian filter is used, which creates a blur effect on an image. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Specifies that filtering is not performed.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Specifies that each destination pixel is computed by sampling the nearest pixel from the source image.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Specifies that linear interpolation is performed using the weighted average of a 2x2 area of pixels surrounding the source pixel.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Specifies that each pixel in the source image contributes equally to the destination image. This is the slowest of filtering algorithms.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Specifies a box filter algorithm, in which each destination pixel is computed by averaging a rectangle of source pixels. This algorithm is useful only when reducing the size of an image.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Specifies that a 4-sample tent filter is used.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Specifies that a 4-sample Gaussian filter is used, which creates a blur effect on an image.

