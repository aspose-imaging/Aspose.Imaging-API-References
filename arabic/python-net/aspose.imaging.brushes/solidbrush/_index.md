---
title: "فئة SolidBrush"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.brushes/solidbrush/
---

**Summary:** Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.SolidBrush

**Inheritance:** Brush

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [SolidBrush()](#SolidBrush__1) | يُنشئ مثيلاً جديدًا من فئة [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
| [SolidBrush(color)](#SolidBrush_color_2) | يُنشئ مثيلاً جديدًا من فئة [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [color](#color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يضبط لون الفرشاة. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| opacity | float | r/w | يحصل أو يعيّن شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة بالكامل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Constructor: SolidBrush() {#SolidBrush__1}


```
 SolidBrush() 
```

يُنشئ مثيلاً جديدًا من فئة [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Constructor: SolidBrush(color) {#SolidBrush_color_2}


```
 SolidBrush(color) 
```

يُنشئ مثيلاً جديدًا من فئة [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | لون الفرشاة الصلبة. |

### Property: color {#color1}

يحصل أو يضبط لون الفرشاة.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

ينشئ نسخة عميقة جديدة من [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة جديدة [Brush](/imaging/python-net/aspose.imaging/brush/) وهي النسخة العميقة من هذه الحالة من [Brush](/imaging/python-net/aspose.imaging/brush/). |


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

