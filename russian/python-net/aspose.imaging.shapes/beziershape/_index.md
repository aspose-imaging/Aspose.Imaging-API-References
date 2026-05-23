---
title: "Класс BezierShape"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы объекта. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает центр фигуры. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает конечную точку фигуры. |
| has_segments | bool | r | Возвращает значение, указывающее, имеет ли фигура сегменты. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыта ли фигура. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает точки кривой. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Возвращает сегменты фигуры. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает начальную точку фигуры. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| reverse() | Изменяет порядок точек этой фигуры на обратный. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к форме. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Инициализирует новый экземпляр класса [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| is_closed | bool | Если установить значение <c>true</c>, кривая Безье замкнута. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Применяет указанное преобразование к форме.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Преобразование для применения. |

