---
title: "PointExtensions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene métodos de extensión para las estructuras Point y PointF."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Contiene métodos de extensión para las estructuras `Point` y `PointF`.
## Métodos

| Método | Descripción |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Convierte la matriz `Point` al arreglo `PointF`. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Convierte la matriz `PointF` al arreglo `System.Drawing.PointF`. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Convierte el `PointF` a `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Convierte la matriz `Point` al arreglo `PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | El arreglo `Point` a convertir. |

**Returns:**
com.aspose.imaging.PointF[] - El arreglo `PointF` convertido.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Convierte la matriz `PointF` al arreglo `System.Drawing.PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | El arreglo `PointF` a convertir. |

**Returns:**
java.awt.geom.Point2D.Float[] - El arreglo `System.Drawing.PointF` convertido.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Convierte el `PointF` a `System.Drawing.PointF`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | El `PointF` a convertir. |

**Returns:**
java.awt.geom.Point2D.Float - El `System.Drawing.PointF` convertido.
