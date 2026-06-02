---
title: "StreamSource فئة"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream)](#StreamSource_stream_2) | يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | يحصل على قيمة تُشير إلى ما إذا كان يجب التخلص من الدفق كلما تم التخلص من الحاوية. |
| دفق | _io.BufferedRandom | r | يحصل على الدفق. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | يحصل على حاوية الدفق. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للفتح. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

يُنشئ مثلاً جديدًا من الفئة [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق للفتح. |
| dispose_stream | bool | إذا تم تعيينه إلى <c>true</c> سيتم التخلص من الدفق. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

يحصل على حاوية الدفق.

**Returns**

| نوع | الوصف |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# يُنشئ مثلاً من JpegOptions ويضبط خصائصه المتنوعة
with JpegOptions() as jpegOptions:
	# أنشئ مثلاً من الدفق
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#عرّف خاصية المصدر للمثَل من JpegOptions
		#المعامل المنطقي الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق
		jpegOptions.source = StreamSource(stream, True)
		#يُنشئ مثلاً من Image ويستدعي طريقة Create مع JpegOptions كمعامل لتهيئة كائن Image
		with Image.create(jpegOptions, 500, 500) as image:
			#قم ببعض معالجة الصورة
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# إنشاء نسخة من MemoryStream
with strm_ext.create_memory_stream() as stream:
	#أنشئ مثيلًا من GifOptions واضبط خصائصه المتنوعة بما في ذلك خاصية Source.
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# إنشاء نسخة من Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# احصل على بكسلات الصورة بتحديد المنطقة كحدود الصورة.
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل.
			for index in range(pixel.length):
				if index % 2 == 0:
					#عيّن لون البكسل المفهرس إلى الأصفر.
					pixels[index] = yellow_color
				else:
					#عيّن لون البكسل المفهرس إلى الأزرق.
					pixels[index] = blue_color

			#طبق تغييرات البكسل على الصورة.
			image.save_pixels(image.bounds, pixels)

			# احفظ جميع التغييرات.
			image.save()

	# اكتب MemoryStream إلى ملف.
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

#ينشئ مثيلاً من تدفق الملف.
with open(r"C:\temp\output.png", "w+b") as stream:
	#إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة.
	pngOptions = PngOptions()
	#تعيين المصدر لـ PngOptions.
	pngOptions.source = StreamSource(stream)
	#إنشاء مثيل من Image.
	with Image.create(pngOptions, 500, 500) as image:
		#إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		#مسح سطح Graphics.
		graphics.clear(Color.wheat);
		#ارسم قوسًا بتحديد كائن Pen الذي لديه لون أسود،
		#مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#ارسم منحنى Bezier بتحديد كائن Pen الذي لديه لون أزرق ونقاط الإحداثيات.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#ارسم منحنى عن طريق تحديد كائن Pen ذو اللون الأخضر ومصفوفة من Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#ارسم إهليلجًا باستخدام كائن Pen ومستطيل محيط
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#ارسم خطًا
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#ارسم قطعة فطيرة
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#ارسم مضلعًا بتحديد كائن Pen ذو اللون الأحمر ومصفوفة من Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#ارسم مستطيلًا
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
		brush = SolidBrush()
		brush.color = Color.purple
		#ارسم نصًا باستخدام كائن SolidBrush و Font، عند نقطة محددة
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# احفظ جميع التغييرات.
		image.save();

```

