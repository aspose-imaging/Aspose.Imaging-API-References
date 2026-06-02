---
title: "PointExtensions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält Erweiterungsmethoden für die Point- und PointF-Strukturen."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Enthält Erweiterungsmethoden für die Strukturen `Point` und `PointF`.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Konvertiert das `Point`-Array zum `PointF`-Array. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Konvertiert das `PointF`-Array zum `System.Drawing.PointF`-Array. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Konvertiert das `PointF` zu `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Konvertiert das `Point`-Array zum `PointF`-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Das `Point`-Array zum Konvertieren. |

**Returns:**
com.aspose.imaging.PointF[] - Das konvertierte `PointF`-Array.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Konvertiert das `PointF`-Array zum `System.Drawing.PointF`-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das `PointF`-Array zum Konvertieren. |

**Returns:**
java.awt.geom.Point2D.Float[] - Das konvertierte `System.Drawing.PointF`-Array.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Konvertiert das `PointF` zu `System.Drawing.PointF`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Das `PointF` zum Konvertieren. |

**Returns:**
java.awt.geom.Point2D.Float - Das konvertierte `System.Drawing.PointF`.
