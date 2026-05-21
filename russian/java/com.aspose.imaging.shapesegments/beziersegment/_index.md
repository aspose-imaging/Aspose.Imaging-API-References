---
title: "BezierSegment"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Кривая Безье, идущая от одной точки к следующей и использующая две контрольные точки."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Кривая Безье, идущая от одной точки к следующей и использующая две контрольные точки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Инициализирует новый экземпляр класса `BezierSegment`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Получает первую управляющую точку безье-сплайна. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Получает вторую управляющую точку безье-сплайна. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Инициализирует новый экземпляр класса `BezierSegment`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Начальная точка. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | Первая управляющая точка. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | Вторая управляющая точка. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Конечная точка. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Получает первую управляющую точку безье-сплайна.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Получает вторую управляющую точку безье-сплайна.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
