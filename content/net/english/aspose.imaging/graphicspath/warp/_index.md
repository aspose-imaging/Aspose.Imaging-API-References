---
title: Warp
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 200
url: /aspose.imaging/graphicspath/warp/
---
## GraphicsPath.Warp method (1 of 4)

Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | An array of [`PointF`](../../pointf) structures that define a parallelogram to which the rectangle defined by *srcRect* is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | RectangleF | A [`RectangleF`](../../rectanglef) that represents the rectangle that is transformed to the parallelogram defined by *destPoints*. |

### See Also

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* namespace [Aspose.Imaging](../../graphicspath)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath.Warp method (2 of 4)

Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | An array of [`PointF`](../../pointf) structures that define a parallelogram to which the rectangle defined by *srcRect* is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | RectangleF | A [`RectangleF`](../../rectanglef) that represents the rectangle that is transformed to the parallelogram defined by *destPoints*. |
| matrix | Matrix | A [`Matrix`](../../matrix) that specifies a geometric transform to apply to the path. |

### See Also

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* namespace [Aspose.Imaging](../../graphicspath)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath.Warp method (3 of 4)

Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | An array of [`PointF`](../../pointf) structures that defines a parallelogram to which the rectangle defined by *srcRect* is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | RectangleF | A [`RectangleF`](../../rectanglef) that represents the rectangle that is transformed to the parallelogram defined by *destPoints*. |
| matrix | Matrix | A [`Matrix`](../../matrix) that specifies a geometric transform to apply to the path. |
| warpMode | WarpMode | A [`WarpMode`](../../warpmode) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |

### See Also

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* namespace [Aspose.Imaging](../../graphicspath)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath.Warp method (4 of 4)

Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | An array of [`PointF`](../../pointf) structures that define a parallelogram to which the rectangle defined by *srcRect* is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | RectangleF | A [`RectangleF`](../../rectanglef) that represents the rectangle that is transformed to the parallelogram defined by *destPoints*. |
| matrix | Matrix | A [`Matrix`](../../matrix) that specifies a geometric transform to apply to the path. |
| warpMode | WarpMode | A [`WarpMode`](../../warpmode) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |
| flatness | Single | A value from 0 through 1 that specifies how flat the resulting path is. For more information, see the [`Flatten`](../flatten) methods. |

### See Also

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* namespace [Aspose.Imaging](../../graphicspath)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
