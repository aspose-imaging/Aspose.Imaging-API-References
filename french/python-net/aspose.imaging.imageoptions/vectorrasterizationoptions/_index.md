---
title: "VectorRasterizationOptions Classe"
type: docs
weight: 350
url: /fr/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Initialise une nouvelle instance de la classe VectorRasterizationOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une couleur d'arrière-plan. |
| border_x | float | r/w | Obtient ou définit la bordure X. |
| border_y | float | r/w | Obtient ou définit la bordure Y. |
| center_drawing | bool | r/w | Obtient ou définit une valeur indiquant si le dessin est centré. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une couleur de premier plan. |
| page_height | float | r/w | Obtient ou définit la hauteur de la page.<br/>            Si la valeur est 0, le rapport d'aspect de l'image source sera conservé. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Obtient ou définit la taille de la page.<br/>            Si l'une des dimensions de [SizeF](/imaging/python-net/aspose.imaging/sizef/) est 0, le rapport d'aspect de l'image source sera conservé. |
| page_width | float | r/w | Obtient ou définit la largeur de la page.<br/>            Si la valeur est 0, le rapport d'aspect de l'image source sera conservé. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Obtient ou définit le positionnement. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtient ou définit l'indice de rendu du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un nouvel objet qui est une copie superficielle de l'instance actuelle. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copie vers. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Initialise une nouvelle instance de la classe VectorRasterizationOptions.

### Property: background_color {#background_color1}

Obtient ou définit une couleur d'arrière-plan.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Obtient ou définit la taille de la page.<br/>            Si l'une des dimensions de [SizeF](/imaging/python-net/aspose.imaging/sizef/) est 0, le rapport d'aspect de l'image source sera conservé.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Obtient ou définit le positionnement.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Crée un nouvel objet qui est une copie superficielle de l'instance actuelle.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Un nouvel objet qui est une copie superficielle de cette instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copie vers.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Les options de rastérisation vectorielle. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Le texte sera converti en formes.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# La couleur d'arrière-plan de la surface de dessin.
	rasterizationOptions.background_color = Color.white_smoke
	# La taille de la page.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
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
	
# Définir une limite de mémoire de 10 mégaoctets pour l'image chargée cible.
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

