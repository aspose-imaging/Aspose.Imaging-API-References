---
title: "فئة OdgRasterizationOptions"
type: docs
weight: 220
url: /ar/python-net/aspose.imaging.imageoptions/odgrasterizationoptions/
---

**Summary:** The Odg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OdgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions__1) | يُنشئ مثلاً جديداً من فئة OdgRasterizationOptions |
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
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | ينسخ إلى. |


### Constructor: OdgRasterizationOptions() {#OdgRasterizationOptions__1}


```
 OdgRasterizationOptions() 
```

يُنشئ مثلاً جديداً من فئة OdgRasterizationOptions

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

ينسخ إلى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | خيارات التحويل النقطي للمتجه. |

## **Examples**
### The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format. {#example_189}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import OdgRasterizationOptions, PdfOptions

dir_: str = "c:\\aspose.imaging\\issues\\net\\3635"
input_file_name: str = join(dir_, "VariousObjectsMultiPage.fodg")
output_file_name: str = input_file_name + ".pdf"
with Image.load(input_file_name) as image:
	rasterization_options = OdgRasterizationOptions()
	rasterization_options.background_color = Color.white
	rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	save_options = PdfOptions()
	save_options.vector_rasterization_options = rasterization_options
	image.save(output_file_name, save_options)


```

