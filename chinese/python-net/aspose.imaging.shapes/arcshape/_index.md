---
title: "ArcShape 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | 初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。 |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | 初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。 |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | 初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取对象的边界。 |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取形状的中心。 |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取结束形状点。 |
| has_segments | bool | r | 获取一个值，指示形状是否具有段。 |
| is_closed | bool | r/w | 获取或设置一个值，指示有序形状是否闭合。在处理闭合的有序形状时，起始点和结束点没有意义。 |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左下矩形点。 |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左上矩形点。 |
| rectangle_height | float | r | 获取矩形高度。 |
| rectangle_width | float | r | 获取矩形宽度。 |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右下矩形点。 |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右上矩形点。 |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | 获取形状的段。 |
| start_angle | float | r/w | 获取或设置起始角度。 |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取起始形状点。 |
| sweep_angle | float | r/w | 获取或设置扫掠角度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| reverse() | 反转此形状的点顺序。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 矩形。 |
| start_angle | float | 起始角度。 |
| sweep_angle | float | 扫掠角。 |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

初始化 [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 矩形。 |
| start_angle | float | 起始角度。 |
| sweep_angle | float | 扫掠角。 |
| is_closed | bool | 如果设置为 <c>true</c>，arc 将闭合。闭合的 arc 实际上退化为椭圆。 |

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

