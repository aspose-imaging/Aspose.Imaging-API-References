---
title: "Classe VectorRasterizationOptions"
type: docs
weight: 350
url: /it/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | Inizializza una nuova istanza della classe VectorRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di sfondo. |
| border_x | float | r/w | Ottiene o imposta il bordo X. |
| border_y | float | r/w | Ottiene o imposta il bordo Y. |
| center_drawing | bool | r/w | Ottiene o imposta un valore che indica se il disegno è centrato. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di primo piano. |
| page_height | float | r/w | Ottiene o imposta l'altezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Ottiene o imposta la dimensione della pagina.<br/>            Se una delle dimensioni di [SizeF](/imaging/python-net/aspose.imaging/sizef/) è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| page_width | float | r/w | Ottiene o imposta la larghezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Ottiene o imposta il posizionamento. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Ottiene o imposta la modalità di smussatura. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Ottiene o imposta il suggerimento di rendering del testo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuovo oggetto che è una copia superficiale dell'istanza corrente. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia in. |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

Inizializza una nuova istanza della classe VectorRasterizationOptions

### Property: background_color {#background_color1}

Ottiene o imposta un colore di sfondo.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

Ottiene o imposta la dimensione della pagina.<br/>            Se una delle dimensioni di [SizeF](/imaging/python-net/aspose.imaging/sizef/) è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

Ottiene o imposta il posizionamento.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuovo oggetto che è una copia superficiale dell'istanza corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Un nuovo oggetto che è una copia superficiale di questa istanza. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copia in.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | Le opzioni di rasterizzazione vettoriale. |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Il testo verrà convertito in forme.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Il colore di sfondo della superficie di disegno.
	rasterizationOptions.background_color = Color.white_smoke
	# La dimensione della pagina.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Se esiste un emf incorporato, renderizzare emf; altrimenti renderizzare wmf.
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
	
# Impostazione di un limite di memoria di 10 megabyte per un'immagine caricata di destinazione.
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

