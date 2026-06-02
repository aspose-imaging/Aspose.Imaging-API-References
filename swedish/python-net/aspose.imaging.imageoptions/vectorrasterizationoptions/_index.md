---
title: "VectorRasterizationOptions klass"
type: docs
weight: 350
url: /sv/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Initierar en ny instans av VectorRasterizationOptions-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger en bakgrundsfärg. |
| border_x | float | r/w | Hämtar eller anger gränsen X. |
| border_y | float | r/w | Hämtar eller anger gränsen Y. |
| center_drawing | bool | r/w | Hämtar eller anger ett värde som indikerar om ritning ska centreras. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger en förgrundsfärg. |
| page_height | float | r/w | Hämtar eller anger sidans höjd.<br/>            Om värdet är 0 bevaras källbildens bildförhållande. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Hämtar eller anger sidans storlek.<br/>            Om någon av [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensionerna är 0 bevaras källbildens bildförhållande. |
| page_width | float | r/w | Hämtar eller anger sidans bredd.<br/>            Om värdet är 0 bevaras källbildens bildförhållande. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Hämtar eller anger positioneringen. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Hämtar eller anger tips för textrendering. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar ett nytt objekt som är en ytlig kopia av den aktuella instansen. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopierar till. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Initierar en ny instans av VectorRasterizationOptions-klassen

### Property: background_color {#background_color1}

Hämtar eller anger en bakgrundsfärg.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Hämtar eller anger sidans storlek.<br/>            Om någon av [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensionerna är 0 bevaras källbildens bildförhållande.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Hämtar eller anger positioneringen.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Skapar ett nytt objekt som är en ytlig kopia av den aktuella instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | Ett nytt objekt som är en ytlig kopia av denna instans. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopierar till.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Alternativen för vektorrasterisering. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att läsa in alla bildtyper inklusive WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Text kommer att konverteras till former.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Bakgrundsfärgen på ritytan.
	rasterizationOptions.background_color = Color.white_smoke
	# Sidstorleken.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Om inbäddad emf finns, rendera emf; annars rendera wmf.
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
	
# Ställer in en minnesgräns på 10 megabyte för en målindladdad bild.
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

