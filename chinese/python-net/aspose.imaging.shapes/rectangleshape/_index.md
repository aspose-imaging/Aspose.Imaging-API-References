---
title: "RectangleShape 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | 初始化 [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/) 类的新实例。 |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | 初始化 [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取对象的边界。 |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取形状的中心。 |
| has_segments | bool | r | 获取一个值，指示形状是否具有段。 |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左下矩形点。 |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左上矩形点。 |
| rectangle_height | float | r | 获取矩形高度。 |
| rectangle_width | float | r | 获取矩形宽度。 |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右下矩形点。 |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右上矩形点。 |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | 获取形状的段。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

初始化 [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/) 类的新实例。

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

初始化 [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 矩形。 |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


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

