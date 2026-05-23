---
title: "VectorRasterizationOptions Clase"
type: docs
weight: 350
url: /es/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Inicializa una nueva instancia de la clase VectorRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un color de fondo. |
| border_x | float | r/w | Obtiene o establece el border X. |
| border_y | float | r/w | Obtiene o establece el border Y. |
| center_drawing | bool | r/w | Obtiene o establece un valor que indica si center drawing. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un color de primer plano. |
| page_height | float | r/w | Obtiene o establece la altura de la página.<br/>            Si el valor es 0, se preservará la relación de aspecto de la imagen de origen. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtiene o establece el tamaño de la página.<br/>            Si una de las dimensiones de [SizeF](/imaging/python-net/aspose.imaging/sizef/) es 0, se preservará la relación de aspecto de la imagen de origen. |
| page_width | float | r/w | Obtiene o establece el ancho de la página.<br/>            Si el valor es 0, se preservará la relación de aspecto de la imagen de origen. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Obtiene o establece la posición. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuevo objeto que es una copia superficial de la instancia actual. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia a. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Inicializa una nueva instancia de la clase VectorRasterizationOptions

### Property: background_color {#background_color1}

Obtiene o establece un color de fondo.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Obtiene o establece el tamaño de la página.<br/>            Si una de las dimensiones de [SizeF](/imaging/python-net/aspose.imaging/sizef/) es 0, se preservará la relación de aspecto de la imagen de origen.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Obtiene o establece la posición.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuevo objeto que es una copia superficial de la instancia actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Un nuevo objeto que es una copia superficial de esta instancia. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copia a.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Las opciones de rasterización vectorial. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# El texto se convertirá en formas.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# El color de fondo de la superficie de dibujo.
	rasterizationOptions.background_color = Color.white_smoke
	# El tamaño de página.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Si existe un emf incrustado, renderiza emf; de lo contrario renderiza wmf.
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
	
# Estableciendo un límite de memoria de 10 megabytes para una imagen cargada objetivo.
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

