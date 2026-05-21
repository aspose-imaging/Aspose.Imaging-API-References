---
title: "PointExtensions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит методы расширения для структур Point и PointF."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

Содержит методы-расширения для структур `Point` и `PointF`.
## Методы

| Метод | Описание |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | Преобразует массив `Point` в массив `PointF`. |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | Преобразует массив `PointF` в массив `System.Drawing.PointF`. |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | Преобразует `PointF` в `System.Drawing.PointF`. |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


Преобразует массив `Point` в массив `PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Массив `Point` для преобразования. |

**Returns:**
com.aspose.imaging.PointF[] - преобразованный массив `PointF`.
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


Преобразует массив `PointF` в массив `System.Drawing.PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив `PointF` для преобразования. |

**Returns:**
java.awt.geom.Point2D.Float[] - преобразованный массив `System.Drawing.PointF`.
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


Преобразует `PointF` в `System.Drawing.PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `PointF` для преобразования. |

**Returns:**
java.awt.geom.Point2D.Float - преобразованный `System.Drawing.PointF`.
