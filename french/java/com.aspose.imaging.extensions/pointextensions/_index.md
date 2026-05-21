---
title: "PointExtensions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient des méthodes d'extension pour les structures Point et PointF."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Contient des méthodes d'extension pour les structures `Point` et `PointF`.
## Méthodes

| Méthode | Description |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Convertit le tableau `Point` en tableau `PointF`. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Convertit le tableau `PointF` en tableau `System.Drawing.PointF`. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Convertit le `PointF` en `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Convertit le tableau `Point` en tableau `PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Le tableau `Point` à convertir. |

**Returns:**
com.aspose.imaging.PointF[] - Le tableau `PointF` converti.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Convertit le tableau `PointF` en tableau `System.Drawing.PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau `PointF` à convertir. |

**Returns:**
java.awt.geom.Point2D.Float[] - Le tableau `System.Drawing.PointF` converti.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Convertit le `PointF` en `System.Drawing.PointF`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Le `PointF` à convertir. |

**Returns:**
java.awt.geom.Point2D.Float - Le `System.Drawing.PointF` converti.
