---
title: "فئة VectorRasterizationOptions"
type: docs
weight: 350
url: /ar/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | ينشئ مثلاً جديداً من فئة VectorRasterizationOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون خلفية. |
| border_x | float | r/w | الحصول أو تعيين الحد X. |
| border_y | float | r/w | الحصول أو تعيين الحد Y. |
| center_drawing | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان يتم الرسم في المركز. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | الحصول أو تعيين لون المقدمة. |
| page_height | float | r/w | الحصول أو تعيين ارتفاع الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | الحصول أو تعيين حجم الصفحة.<br/>            إذا كان أحد أبعاد [SizeF](/imaging/python-net/aspose.imaging/sizef/) يساوي 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_width | float | r/w | الحصول أو تعيين عرض الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | الحصول أو تعيين الموضع. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | ينسخ إلى. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

ينشئ مثلاً جديداً من فئة VectorRasterizationOptions.

### Property: background_color {#background_color1}

يحصل أو يعيّن لون خلفية.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

الحصول أو تعيين حجم الصفحة.<br/>            إذا كان أحد أبعاد [SizeF](/imaging/python-net/aspose.imaging/sizef/) يساوي 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

الحصول أو تعيين الموضع.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


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

### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# تعيين حد الذاكرة إلى 10 ميغابايت لصورة محمّلة مستهدفة.
load_options = LoadOptions()
load_options.buffer_size_hint = 10
with Image.load(os.path.join(directory, "example.cmx"), load_options) as image:
	png_options = PngOptions()
	cmx_spec = CmxRasterizationOptions()
	cmx_spec.text_renderingHint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	cmx_spec.smoothing_mode = SmoothingMode.ANTI_ALIAS
	cmx_spec.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	png_options.vector_rasterization_options = cmx_spec
	image.save(os.path.join(directory, "output.png"), png_options)


```

### The following example shows how to export all pages of CDR document to PDF. {#example_187}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode
from aspose.imaging.imageoptions import PdfOptions, CdrRasterizationOptions, PositioningTypes
from os.path import join

dir_: str = "c:\\3570"
input_cdr_file_name: str = join(dir_, "tiger.cdr")
output_pdf_file_name: str = join(dir_, "tiger.cdr.pdf")
with Image.load(input_cdr_file_name) as image:
	pdf_options = PdfOptions()
	rasterization_options = CdrRasterizationOptions()
	rasterization_options.text_rendering_hint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	rasterization_options.smoothing_mode = SmoothingMode.NONE
	rasterization_options.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	pdf_options.vector_rasterization_options = rasterization_options
	image.save(output_pdf_file_name, pdf_options)


```

