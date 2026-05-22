---
title: "ObjectWithBounds 类"
type: docs
weight: 6220
url: /zh/python-net/aspose.imaging/objectwithbounds/
---

**Summary:** The object having bounds.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ObjectWithBounds

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取对象的边界。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


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

