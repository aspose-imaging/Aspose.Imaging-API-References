---
title: "PointExtensions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Point ve PointF yapılarına yönelik uzantı metodlarını içerir."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

`Point` ve `PointF` yapıları için uzantı metodlarını içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | `Point` dizisini `PointF` dizisine dönüştürür. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | `PointF` dizisini `System.Drawing.PointF` dizisine dönüştürür. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | `PointF` öğesini `System.Drawing.PointF`'e dönüştürür. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


`Point` dizisini `PointF` dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Dönüştürülecek `Point` dizisi. |

**Returns:**
com.aspose.imaging.PointF[] - Dönüştürülmüş `PointF` dizisi.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


`PointF` dizisini `System.Drawing.PointF` dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Dönüştürülecek `PointF` dizisi. |

**Returns:**
java.awt.geom.Point2D.Float[] - Dönüştürülmüş `System.Drawing.PointF` dizisi.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


`PointF` öğesini `System.Drawing.PointF`'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Dönüştürülecek `PointF`. |

**Returns:**
java.awt.geom.Point2D.Float - Dönüştürülmüş `System.Drawing.PointF`.
