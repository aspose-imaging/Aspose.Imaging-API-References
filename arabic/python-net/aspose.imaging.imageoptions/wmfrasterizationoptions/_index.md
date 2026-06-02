---
title: "فئة WmfRasterizationOptions"
type: docs
weight: 380
url: /ar/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | يُنشئ مثلاً جديداً من الفئة [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون خلفية. |
| border_x | float | r/w | الحصول أو تعيين الحد X. |
| border_y | float | r/w | الحصول أو تعيين الحد Y. |
| center_drawing | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان يتم الرسم في المركز. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | الحصول أو تعيين لون المقدمة. |
| page_height | float | r/w | الحصول أو تعيين ارتفاع الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | الحصول أو تعيين حجم الصفحة.<br/>            إذا كان أحد أبعاد [SizeF](/imaging/python-net/aspose.imaging/sizef/) يساوي 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_width | float | r/w | الحصول أو تعيين عرض الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | الحصول أو تعيين الموضع. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | يحصل أو يضبط وضع عرض WMF. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | ينسخ هذا إلى _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

يُنشئ مثلاً جديداً من الفئة [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/).

### Property: render_mode {#render_mode1}

يحصل أو يضبط وضع عرض WMF.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | كائن جديد هو نسخة سطحية من هذا المثيل. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

ينسخ هذا إلى _vectorRasterizationOptions_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# سيتم تحويل النص إلى أشكال.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# لون الخلفية لسطح الرسم.
	rasterizationOptions.background_color = Color.white_smoke
	# حجم الصفحة.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

