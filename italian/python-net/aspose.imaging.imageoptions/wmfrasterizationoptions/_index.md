---
title: "WmfRasterizationOptions Classe"
type: docs
weight: 380
url: /it/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Inizializza una nuova istanza della classe [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di sfondo. |
| border_x | float | r/w | Ottiene o imposta il bordo X. |
| border_y | float | r/w | Ottiene o imposta il bordo Y. |
| center_drawing | bool | r/w | Ottiene o imposta un valore che indica se il disegno è centrato. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un colore di primo piano. |
| page_height | float | r/w | Ottiene o imposta l'altezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Ottiene o imposta la dimensione della pagina.<br/>            Se una delle dimensioni di [SizeF](/imaging/python-net/aspose.imaging/sizef/) è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| page_width | float | r/w | Ottiene o imposta la larghezza della pagina.<br/>            Se il valore è 0, il rapporto d'aspetto dell'immagine di origine verrà mantenuto. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Ottiene o imposta il posizionamento. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Ottiene o imposta la modalità di rendering WMF. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Ottiene o imposta la modalità di smussatura. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Ottiene o imposta il suggerimento di rendering del testo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuovo oggetto che è una copia superficiale dell'istanza corrente. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia questo in _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Inizializza una nuova istanza della classe [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/).

### Property: render_mode {#render_mode1}

Ottiene o imposta la modalità di rendering WMF.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

Copia questo in _vectorRasterizationOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

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

