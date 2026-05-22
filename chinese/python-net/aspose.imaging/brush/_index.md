---
title: "Brush 类"
type: docs
weight: 340
url: /zh/python-net/aspose.imaging/brush/
---

**Summary:** The base brush class.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Brush

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| [opacity](#opacity1) | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |


### Property: opacity {#opacity1}

获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个新的 [Brush](/imaging/python-net/aspose.imaging/brush/)，它是此 [Brush](/imaging/python-net/aspose.imaging/brush/) 实例的深度克隆。 |


## **Examples**
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#创建文件流的实例
with open(r"C:\temp\output.png", "w+b") as stream:
	#创建 PngOptions 实例并设置其各种属性
	pngOptions = PngOptions()
	#设置 PngOptions 的 Source
	pngOptions.source = StreamSource(stream)
	#创建 Image 实例
	with Image.create(pngOptions, 500, 500) as image:
		#创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		#清除 Graphics 表面
		graphics.clear(Color.wheat);
		#通过指定具有黑色的 Pen 对象来绘制弧线，
		#一个围绕弧线的矩形、起始角度和扫掠角度
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#通过指定具有蓝色的 Pen 对象和坐标点来绘制贝塞尔曲线。
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#通过指定具有绿色颜色的 Pen 对象和一个点数组来绘制曲线
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#使用 Pen 对象和一个包围的矩形绘制椭圆
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#绘制直线
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#绘制饼图扇形
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#通过指定具有红色颜色的 Pen 对象和一个点数组来绘制多边形
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#绘制矩形
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#创建 SolidBrush 对象并设置其各种属性
		brush = SolidBrush()
		brush.color = Color.purple
		#使用 SolidBrush 对象和 Font 在特定点绘制字符串
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# 保存所有更改。
		image.save();

```

