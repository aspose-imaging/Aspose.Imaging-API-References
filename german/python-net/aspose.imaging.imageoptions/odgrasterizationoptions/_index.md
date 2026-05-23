---
title: "OdgRasterizationOptions Klasse"
type: docs
weight: 220
url: /de/python-net/aspose.imaging.imageoptions/odgrasterizationoptions/
---

**Summary:** The Odg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OdgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions__1) | Initialisiert eine neue Instanz der OdgRasterizationOptions Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Legt eine Hintergrundfarbe fest oder ruft sie ab. |
| border_x | float | r/w | Liest oder setzt den Rand X. |
| border_y | float | r/w | Liest oder setzt den Rand Y. |
| center_drawing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Zeichnen zentriert ist. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt eine Vordergrundfarbe. |
| page_height | float | r/w | Liest oder setzt die Seitenhöhe.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Liest oder setzt die Seitengröße.<br/>            Wenn eine der [SizeF](/imaging/python-net/aspose.imaging/sizef/) Dimensionen 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| page_width | float | r/w | Liest oder setzt die Seitenbreite.<br/>            Wenn der Wert 0 ist, wird das Seitenverhältnis des Quellbildes beibehalten. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Liest oder setzt die Positionierung. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Liest oder setzt den Glättungsmodus. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Liest oder setzt den Hinweis zur Textdarstellung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopiert nach. |


### Constructor: OdgRasterizationOptions() {#OdgRasterizationOptions__1}


```
 OdgRasterizationOptions() 
```

Initialisiert eine neue Instanz der OdgRasterizationOptions Klasse

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

