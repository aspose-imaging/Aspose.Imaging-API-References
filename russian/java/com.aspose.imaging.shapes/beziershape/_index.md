---
title: "BezierShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет сплайн Безье."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Представляет сплайн Безье.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BezierShape()](#BezierShape--) | Инициализирует новый экземпляр класса `BezierShape`. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Инициализирует новый экземпляр класса `BezierShape`. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Инициализирует новый экземпляр класса `BezierShape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getCenter()](#getCenter--) | Получает центр фигуры. |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [getEndPoint()](#getEndPoint--) | Получает конечную точку формы. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Инициализирует новый экземпляр класса `BezierShape`.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Инициализирует новый экземпляр класса `BezierShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив точек. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Инициализирует новый экземпляр класса `BezierShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив точек. |
| isClosed | boolean | Если установлено `true`, сплайн Безье замкнут. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает границы объекта.

Значение: Границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Получает центр фигуры.

Значение: Центр формы.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты фигуры.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Получает значение, указывающее, есть ли у фигуры сегменты.

Значение: `True`, если у формы есть сегменты; иначе `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Получает конечную точку формы.

Значение: Конечная точка фигуры.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, применяемая перед вычислением границ. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
