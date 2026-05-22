---
title: "PolygonShape 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | 初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。 |
| [PolygonShape(points)](#PolygonShape_points_2) | 初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。 |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | 初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。 |
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


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

初始化 [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，则多边形闭合。 |

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

## **Examples**
### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#创建 BmpOptions 的实例并设置其各种属性            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#创建 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
	#第二个布尔参数决定要创建的文件是否为临时文件
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#创建 Image 实例
	with Image.create(bmpOptions, 500, 500) as image:
		# 创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		# 清除 Graphics 表面
		graphics.clear(Color.wheat)
		# 创建 GraphicsPath 类的实例
		graphicspath = GraphicsPath()
		#创建 Figure 类的实例
		figure1 = Figure()
		# 向 Figure 对象添加形状
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# 创建 Figure 类的实例
		figure2 = Figure()
		# 向 Figure 对象添加形状
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# 将 Figure 对象添加到 GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# 使用颜色为 Black 的 Pen 对象绘制路径
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# 保存所有更改。
		image.save()


```

