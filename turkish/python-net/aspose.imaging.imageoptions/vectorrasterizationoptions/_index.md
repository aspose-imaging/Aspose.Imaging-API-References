---
title: "VectorRasterizationOptions Sınıfı"
type: docs
weight: 350
url: /tr/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | VectorRasterizationOptions sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan rengini alır veya ayarlar. |
| border_x | float | r/w | Sınır X'i alır veya ayarlar. |
| border_y | float | r/w | Sınır Y'yi alır veya ayarlar. |
| center_drawing | bool | r/w | Orta çizim olup olmadığını gösteren bir değeri alır veya ayarlar. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ön plan rengini alır veya ayarlar. |
| page_height | float | r/w | Sayfa yüksekliğini alır veya ayarlar.<br/>            Değer 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Sayfa boyutunu alır veya ayarlar.<br/>            Eğer [SizeF](/imaging/python-net/aspose.imaging/sizef/) boyutlarından biri 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| page_width | float | r/w | Sayfa genişliğini alır veya ayarlar.<br/>            Değer 0 ise, kaynak görüntünün en‑boy oranı korunur. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Konumlandırmayı alır veya ayarlar. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopyalar. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

VectorRasterizationOptions sınıfının yeni bir örneğini başlatır.

### Property: background_color {#background_color1}

Arka plan rengini alır veya ayarlar.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Sayfa boyutunu alır veya ayarlar.<br/>            Eğer [SizeF](/imaging/python-net/aspose.imaging/sizef/) boyutlarından biri 0 ise, kaynak görüntünün en‑boy oranı korunur.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Konumlandırmayı alır veya ayarlar.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Geçerli örneğin yüzeysel bir kopyası olan yeni bir nesne oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Bu örneğin yüzeysel bir kopyası olan yeni bir nesne. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Vektör rasterleştirme seçenekleri. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Metin şekillere dönüştürülecek.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Çizim yüzeyinin arka plan rengi.
	rasterizationOptions.background_color = Color.white_smoke
	# Sayfa boyutu.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Gömülü emf varsa, emf işlenir; aksi takdirde wmf işlenir.
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
	
# Hedef yüklenen görüntü için 10 megabayt bellek sınırı ayarlanıyor.
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

