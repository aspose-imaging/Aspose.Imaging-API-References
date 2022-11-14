---
title: OdGradientStyle
second_title: Aspose.Imaging for Java API Reference
description: The gradient style
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

The gradient style
## Fields

| Field | Description |
| --- | --- |
| [Axial](#Axial) | The axial defines a bi-linear gradient that is also known as reflected gradient or mirrored linear gradient. |
| [Ellipsoid](#Ellipsoid) | The ellipsoid defines a gradient where the colors are blend along the radius from the center of an ellipsoid as defined with the draw:cx and draw:cy attributes. |
| [Linear](#Linear) | The linear defines a gradient where the colors blend along the linear axis of the gradient. |
| [Radial](#Radial) | The radial defines a gradient where the colors are blend along the radius from the center of a circle as defined with the draw:cx and draw:cy attributes. |
| [Rectangle](#Rectangle) | The rectangle defines a gradient that produces a rectangular blend from the center of the rectangle to the shortest of the 4 borders. |
| [Square](#Square) | The square defines a gradient that produces a square blend, imitating the visual perspective in a corridor or the aerial view of a pyramid. |
| [None](#None) | The gradient style is none |
### Axial {#Axial}
```
public static final int Axial
```


The axial defines a bi-linear gradient that is also known as reflected gradient or mirrored linear gradient. It is created as a linear gradient that is mirrored (or reflected) along its axis.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


The ellipsoid defines a gradient where the colors are blend along the radius from the center of an ellipsoid as defined with the draw:cx and draw:cy attributes. The length of the semi major-axis is the width of the filled area and the length of the semi-minor

### Linear {#Linear}
```
public static final int Linear
```


The linear defines a gradient where the colors blend along the linear axis of the gradient. The axis of the gradient is specified with the draw:angle attribute clockwise to the vertical axis.

### Radial {#Radial}
```
public static final int Radial
```


The radial defines a gradient where the colors are blend along the radius from the center of a circle as defined with the draw:cx and draw:cy attributes. The outside of the circle is filled with the end color.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


The rectangle defines a gradient that produces a rectangular blend from the center of the rectangle to the shortest of the 4 borders. The center of the rectangle is defined with the attributes draw:cx and draw:cy. The width of the rectangle is the width of the filled area, the height of the rectangle is the height of the filled area. The outside of the square is filled with the end color.

### Square {#Square}
```
public static final int Square
```


The square defines a gradient that produces a square blend, imitating the visual perspective in a corridor or the aerial view of a pyramid. Also known as "box gradient" and "pyramidal gradient". The center of the square is defined with the draw:cx and draw:cy attributes. The width and height of the square is the minimum value of either the width or the height of the filled area. The outside of the square is filled with the end color.

### None {#None}
```
public static final int None
```


The gradient style is none

