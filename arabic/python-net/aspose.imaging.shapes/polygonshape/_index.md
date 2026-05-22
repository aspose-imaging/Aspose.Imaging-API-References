---
title: "فئة PolygonShape"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود الكائن. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على مركز الشكل. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة النهاية للشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| is_closed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن نقاط المنحنى. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | يحصل على مقاطع الشكل. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة بداية الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

ينشئ نسخة جديدة من الفئة [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> فإن المضلع مغلق. |

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

