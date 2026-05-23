---
title: "VectorRasterizationOptions Klasse"
type: docs
weight: 350
url: /de/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Initialisiert eine neue Instanz der VectorRasterizationOptions Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Legt eine Hintergrundfarbe fest oder ruft sie ab. |
| border_x | float | r/w | Liest oder setzt den Rand X. |
| border_y | float | r/w | Liest oder setzt den Rand Y. |
| center_drawing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Zeichnen zentriert ist. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt eine Vordergrundfarbe. |
| page_height | float | r/w | Liest oder setzt die Seitenhöhe.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Liest oder setzt die Seitengröße.<br/>            Wenn eine der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Dimensionen 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| page_width | float | r/w | Liest oder setzt die Seitenbreite.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Liest oder setzt die Positionierung. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Liest oder setzt den Glättungsmodus. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Liest oder setzt den Hinweis zur Textdarstellung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopiert nach. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Initialisiert eine neue Instanz der VectorRasterizationOptions Klasse

### Property: background_color {#background_color1}

Legt eine Hintergrundfarbe fest oder ruft sie ab.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Liest oder setzt die Seitengröße.<br/>            Wenn eine der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Dimensionen 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Liest oder setzt die Positionierung.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Ein neues Objekt, das eine flache Kopie dieser Instanz ist. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopiert nach.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Die Vektor-Rasterisierungsoptionen. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, alle Bildtypen einschließlich WMF zu laden.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Text wird in Formen konvertiert.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Die Hintergrundfarbe der Zeichenfläche.
	rasterizationOptions.background_color = Color.white_smoke
	# Die Seitengröße.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Wenn ein eingebettetes emf vorhanden ist, wird emf gerendert; andernfalls wird wmf gerendert.
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
	
# Festlegen eines Speicherlimits von 10 Megabyte für ein geladenes Zielbild.
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

