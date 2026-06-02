---
title: "Figure 类"
type: docs
weight: 4770
url: /zh/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Figure()](#Figure__1) | 初始化一个新的 [Figure](/imaging/python-net/aspose.imaging/figure/) 实例。<br/>            用于 JSON 反序列化的构造函数。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取或设置对象的边界。 |
| is_closed | bool | r/w | 获取或设置一个值，指示此图形是否闭合。闭合的图形仅在以下情况下才会产生差异：<br/>            第一个和最后一个图形的形状是连续形状的情况下。在这种情况下，第一个形状的第一个点将通过一条直线与最后一个形状的最后一点相连。 |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | 获取整个图形的段。 |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | 获取形状。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | 向图形添加形状。 |
| [add_shapes(shapes)](#add_shapes_shapes_2) | 向图形添加一系列形状。 |
| [get_bounds(matrix)](#get_bounds_matrix_3) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | 获取对象的边界。 |
| [remove_shape(shape)](#remove_shape_shape_5) | 从图形中移除形状。 |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | 从图形中移除一系列形状。 |
| reverse() | 反转此图形的形状顺序和形状点的顺序。 |
| [transform(transform)](#transform_transform_7) | 对形状应用指定的变换。 |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

初始化一个新的 [Figure](/imaging/python-net/aspose.imaging/figure/) 实例。<br/>            用于 JSON 反序列化的构造函数。

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

向图形添加形状。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | 要添加的形状。 |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

向图形添加一系列形状。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | 要添加的形状集合。 |

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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

从图形中移除形状。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | 要移除的形状。 |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

从图形中移除一系列形状。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | 要移除的形状范围。 |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 要应用的变换。 |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# 创建文件流的实例
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# 创建 TiffOptions 的实例并设置其各种属性
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# 为 ImageOptions 实例设置源
	tiffOptions.source = StreamSource(stream)
	# 创建 Image 的实例
	with Image.create(tiffOptions, 500, 500) as image:
		# 创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		# 清除 Graphics 表面
		graphics.clear(Color.wheat);
		# 创建 GraphicsPath 类的实例
		graphics_path = GraphicsPath()
		# 创建 Figure 类的实例
		figure = Figure()
		# 向 Figure 对象添加形状
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# 将 Figure 对象添加到 GraphicsPath
		graphics_path.add_figure(figure)
		# 使用颜色为 Black 的 Pen 对象绘制路径
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# 保存所有更改。
		image.save()


```

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

