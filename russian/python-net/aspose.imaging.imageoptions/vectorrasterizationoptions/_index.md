---
title: "VectorRasterizationOptions Класс"
type: docs
weight: 350
url: /ru/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Инициализирует новый экземпляр класса VectorRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задаёт цвет фона. |
| border_x | float | r/w | Получает или задает границу X. |
| border_y | float | r/w | Получает или задает границу Y. |
| center_drawing | bool | r/w | Получает или задает значение, указывающее, включено ли центрирование рисования. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает цвет переднего плана. |
| page_height | float | r/w | Получает или задает высоту страницы.<br/>            Если значение равно 0, соотношение сторон исходного изображения будет сохранено. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Получает или задает размер страницы.<br/>            Если одно из измерений [SizeF](/imaging/python-net/aspose.imaging/sizef/) равно 0, соотношение сторон исходного изображения будет сохранено. |
| page_width | float | r/w | Получает или задает ширину страницы.<br/>            Если значение равно 0, соотношение сторон исходного изображения будет сохранено. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Получает или задает позиционирование. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Получает или задает режим сглаживания. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Получает или задает подсказку рендеринга текста. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создает новый объект, являющийся поверхностной копией текущего экземпляра. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Копирует в. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Инициализирует новый экземпляр класса VectorRasterizationOptions

### Property: background_color {#background_color1}

Получает или задаёт цвет фона.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Получает или задает размер страницы.<br/>            Если одно из измерений [SizeF](/imaging/python-net/aspose.imaging/sizef/) равно 0, соотношение сторон исходного изображения будет сохранено.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Получает или задает позиционирование.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Создает новый объект, являющийся поверхностной копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Новый объект, являющийся поверхностной копией этого экземпляра. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Копирует в.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Параметры растеризации векторных изображений. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Текст будет преобразован в фигуры.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Цвет фона поверхности рисования.
	rasterizationOptions.background_color = Color.white_smoke
	# Размер страницы.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Если встроенный emf существует, то рендерить emf; иначе рендерить wmf.
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
	
# Установка ограничения памяти в 10 мегабайт для целевого загруженного изображения.
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

