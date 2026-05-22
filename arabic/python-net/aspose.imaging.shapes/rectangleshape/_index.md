---
title: "فئة RectangleShape"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | ينشئ مثيلًا جديدًا من الفئة [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/). |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | ينشئ مثيلًا جديدًا من الفئة [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود الكائن. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على مركز الشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى السفلية. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى العليا. |
| rectangle_height | float | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | float | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى السفلية. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى العليا. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | يحصل على مقاطع الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

ينشئ مثيلًا جديدًا من الفئة [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/).

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

ينشئ مثيلًا جديدًا من الفئة [RectangleShape](/imaging/python-net/aspose.imaging.shapes/rectangleshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | التحويل المراد تطبيقه. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# إنشاء كائن من تدفق ملف
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# تعيين المصدر للنسخة من ImageOptions
	tiffOptions.source = StreamSource(stream)
	# إنشاء نسخة من Image
	with Image.create(tiffOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat);
		# إنشاء نسخة من الفئة GraphicsPath
		graphics_path = GraphicsPath()
		# إنشاء نسخة من الفئة Figure
		figure = Figure()
		# إضافة أشكال إلى كائن Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# إضافة كائن Figure إلى GraphicsPath
		graphics_path.add_figure(figure)
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# احفظ جميع التغييرات.
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

#إنشاء نسخة من BmpOptions وتعيين خصائصه المتنوعة
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#إنشاء نسخة من FileCreateSource وتعيينها كمصدر للنسخة من BmpOptions
	#المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه IsTemporal أم لا
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#إنشاء مثيل من Image.
	with Image.create(bmpOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat)
		# إنشاء نسخة من الفئة GraphicsPath
		graphicspath = GraphicsPath()
		#إنشاء نسخة من الفئة Figure
		figure1 = Figure()
		# إضافة شكل إلى كائن Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# إنشاء نسخة من الفئة Figure
		figure2 = Figure()
		# إضافة شكل إلى كائن Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# إضافة كائن Figure إلى GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# احفظ جميع التغييرات.
		image.save()


```

