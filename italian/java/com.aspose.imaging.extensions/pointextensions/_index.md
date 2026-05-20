---
title: "PointExtensions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene metodi di estensione per le strutture Point e PointF."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Contiene metodi di estensione per le strutture `Point` e `PointF`.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Converte l'array di `Point` nell'array di `PointF`. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Converte l'array di `PointF` nell'array di `System.Drawing.PointF`. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Converte il `PointF` in `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Converte l'array di `Point` nell'array di `PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | L'array `Point` da convertire. |

**Returns:**
com.aspose.imaging.PointF[] - L'array `PointF` convertito.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Converte l'array di `PointF` nell'array di `System.Drawing.PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array `PointF` da convertire. |

**Returns:**
java.awt.geom.Point2D.Float[] - L'array `System.Drawing.PointF` convertito.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Converte il `PointF` in `System.Drawing.PointF`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Il `PointF` da convertire. |

**Returns:**
java.awt.geom.Point2D.Float - Il `System.Drawing.PointF` convertito.
