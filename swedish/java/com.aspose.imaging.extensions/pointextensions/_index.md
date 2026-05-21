---
title: "PointExtensions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller utökningsmetoder för Point- och PointF-strukturer."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Innehåller utökningsmetoder för `Point`‑ och `PointF`‑strukturer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Konverterar `Point`-arrayen till `PointF`-arrayen. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Konverterar `PointF`-arrayen till `System.Drawing.PointF`-arrayen. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Konverterar `PointF` till `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Konverterar `Point`-arrayen till `PointF`-arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | `Point`-arrayen att konvertera. |

**Returns:**
com.aspose.imaging.PointF[] - Den konverterade `PointF`-arrayen.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Konverterar `PointF`-arrayen till `System.Drawing.PointF`-arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | `PointF`-arrayen att konvertera. |

**Returns:**
java.awt.geom.Point2D.Float[] - Den konverterade `System.Drawing.PointF`-arrayen.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Konverterar `PointF` till `System.Drawing.PointF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `PointF` att konvertera. |

**Returns:**
java.awt.geom.Point2D.Float - Den konverterade `System.Drawing.PointF`.
