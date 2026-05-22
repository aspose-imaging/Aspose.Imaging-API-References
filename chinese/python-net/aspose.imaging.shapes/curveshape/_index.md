---
title: "CurveShape 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。 |
| [CurveShape(points)](#CurveShape_points_2) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。 |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。 |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。 |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。 |
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
| 张力 | float | r/w | 获取或设置曲线张力。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。 |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | 初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。 |
| [get_bounds(matrix)](#get_bounds_matrix_3) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | 获取对象的边界。 |
| reverse() | 反转此形状的点顺序。 |
| [transform(transform)](#transform_transform_5) | 对形状应用指定的变换。 |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，则曲线闭合。 |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| 张力 | float | 曲线张力。 |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| 张力 | float | 曲线张力。 |
| is_closed | bool | 如果设置为 <c>true</c>，则曲线闭合。 |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，则曲线闭合。 |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

初始化一个新的 [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| 张力 | float | 曲线张力。 |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 要应用的变换。 |

