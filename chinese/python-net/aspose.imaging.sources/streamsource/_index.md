---
title: "StreamSource 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | 初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。 |
| [StreamSource(stream)](#StreamSource_stream_2) | 初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。 |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | 初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | 获取一个值，指示在容器被释放时是否应释放流。 |
| 流 | _io.BufferedRandom | r | 获取流。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | 获取流容器。 |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要打开的流。 |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

初始化 [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要打开的流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，流将被释放。 |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

获取流容器。

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# 创建 JpegOptions 的实例并设置其各种属性。
with JpegOptions() as jpegOptions:
	# 创建流的实例。
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#为 JpegOptions 实例定义 source 属性。
		#第二个布尔参数决定 Stream 在超出作用域后是否被释放。
		jpegOptions.source = StreamSource(stream, True)
		#创建 Image 的实例，并使用 JpegOptions 作为参数调用 Create 方法来初始化 Image 对象。
		with Image.create(jpegOptions, 500, 500) as image:
			#进行一些图像处理
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# 创建 MemoryStream 的实例
with strm_ext.create_memory_stream() as stream:
	#创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# 创建 Image 的实例
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# 通过将区域指定为图像边界来获取图像的像素
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#遍历数组并设置交替索引像素的颜色
			for index in range(pixel.length):
				if index % 2 == 0:
					#将索引像素颜色设置为黄色
					pixels[index] = yellow_color
				else:
					#将索引像素颜色设置为蓝色
					pixels[index] = blue_color

			#将像素更改应用于图像
			image.save_pixels(image.bounds, pixels)

			# 保存所有更改。
			image.save()

	# 将 MemoryStream 写入文件
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

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

