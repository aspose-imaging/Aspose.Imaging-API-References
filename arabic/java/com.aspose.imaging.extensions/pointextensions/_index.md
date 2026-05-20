---
title: "PointExtensions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على أساليب امتداد لهياكل Point و PointF."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

يحتوي على أساليب امتداد للهيكليتين `Point` و `PointF`.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | يحوّل مصفوفة `Point` إلى مصفوفة `PointF`. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | يحوّل مصفوفة `PointF` إلى مصفوفة `System.Drawing.PointF`. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | يقوم بتحويل `PointF` إلى `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


يحوّل مصفوفة `Point` إلى مصفوفة `PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | مصفوفة `Point` للتحويل. |

**Returns:**
com.aspose.imaging.PointF[] - مصفوفة `PointF` المحوَّلة.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


يحوّل مصفوفة `PointF` إلى مصفوفة `System.Drawing.PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة `PointF` للتحويل. |

**Returns:**
java.awt.geom.Point2D.Float[] - مصفوفة `System.Drawing.PointF` المحوَّلة.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


يقوم بتحويل `PointF` إلى `System.Drawing.PointF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `PointF` للتحويل. |

**Returns:**
java.awt.geom.Point2D.Float - `System.Drawing.PointF` المحوَّل.
