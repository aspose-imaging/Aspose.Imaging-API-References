---
title: "فئة ArcShape"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود الكائن. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على مركز الشكل. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة النهاية للشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| is_closed | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة الشكل المرتب المغلق لا يكون للنقطة البداية والنقطة النهاية معنى. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى السفلية. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى العليا. |
| rectangle_height | float | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | float | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى السفلية. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى العليا. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | يحصل على مقاطع الشكل. |
| start_angle | float | r/w | يحصل أو يعيّن زاوية البداية. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة بداية الشكل. |
| sweep_angle | float | r/w | يحصل أو يعيّن زاوية القوس. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل. |
| start_angle | float | زاوية البداية. |
| sweep_angle | float | زاوية المسح. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

ينشئ مثيلًا جديدًا من الفئة [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل. |
| start_angle | float | زاوية البداية. |
| sweep_angle | float | زاوية المسح. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> يصبح القوس مغلقًا. القوس المغلق يتحول فعليًا إلى إهليلج. |

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

