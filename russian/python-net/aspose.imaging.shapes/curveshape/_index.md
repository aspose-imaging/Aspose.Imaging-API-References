---
title: "Класс CurveShape"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
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
| натяжение | float | r/w | Получает или задает натяжение кривой. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Получает границы объекта. |
| reverse() | Изменяет порядок точек этой фигуры на обратный. |
| [transform(transform)](#transform_transform_5) | Применяет указанное преобразование к форме. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| is_closed | bool | Если установлено в <c>true</c>, кривая закрыта. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| натяжение | float | Натяжение кривой. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| натяжение | float | Натяжение кривой. |
| is_closed | bool | Если установлено в <c>true</c>, кривая закрыта. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Используется напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| is_closed | bool | Если установлено в <c>true</c>, кривая закрыта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Инициализирует новый экземпляр класса [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| натяжение | float | Натяжение кривой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Применяет указанное преобразование к форме.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Преобразование для применения. |

