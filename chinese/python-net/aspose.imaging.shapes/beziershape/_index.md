---
title: "BezierShape 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | 初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。 |
| [BezierShape(points)](#BezierShape_points_2) | 初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。 |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | 初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取对象的边界。 |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取形状的中心。 |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取结束形状点。 |
| has_segments | bool | r | 获取一个值，指示形状是否具有段。 |
| is_closed | bool | r/w | 获取或设置指示形状是否闭合的值。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置曲线点。 |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | 获取形状的段。 |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取起始形状点。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| reverse() | 反转此形状的点顺序。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

初始化 [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，bezier spline 将闭合。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于对象的笔。这可能会影响对象边界的大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 要应用的变换。 |

