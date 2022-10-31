---
title: PointExtensions
second_title: Aspose.Imaging for Java API Reference
description: Contains extension methods for KKKCODEB PointKKKCODEE and KKKCODEB PointFKKKCODEE structures.
type: docs
weight: 21
url: /java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Contains extension methods for `Point` and `PointF` structures.
## Methods

| Method | Description |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Converts the `Point` array to the `PointF` array. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Converts the `PointF` array to the `System.Drawing.PointF` array. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Converts the `PointF` to `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Converts the `Point` array to the `PointF` array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | The `Point` array to convert. |

**Returns:**
com.aspose.imaging.PointF[] - The converted `PointF` array.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Converts the `PointF` array to the `System.Drawing.PointF` array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The `PointF` array to convert. |

**Returns:**
java.awt.geom.Point2D.Float[] - The converted `System.Drawing.PointF` array.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Converts the `PointF` to `System.Drawing.PointF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `PointF` to convert. |

**Returns:**
java.awt.geom.Point2D.Float - The converted `System.Drawing.PointF`.
