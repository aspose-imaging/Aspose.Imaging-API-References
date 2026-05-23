---
title: "OtgRasterizationOptions Klasse"
type: docs
weight: 230
url: /de/python-net/aspose.imaging.imageoptions/otgrasterizationoptions/
---

**Summary:** The Otg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OtgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions__1) | Initialisiert eine neue Instanz der OtgRasterizationOptions Klasse |
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


### Constructor: OtgRasterizationOptions() {#OtgRasterizationOptions__1}


```
 OtgRasterizationOptions() 
```

Initialisiert eine neue Instanz der OtgRasterizationOptions Klasse

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
### The following code snippet demonstrates how to convert an OTG image to PDF and other image formats. {#example_183}
``` python

from aspose.pycore import cast
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import PngOptions, PdfOptions, OtgRasterizationOptions

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "VariousObjectsMultiPage.otg"
options = [PngOptions(), PdfOptions()]
for save_options in options:
	extension: str = ".png" if aspycore.is_assignable(save_options, PngOptions) else ".pdf"
	with Image.load(input_file_path) as image:
		otg_rasterization_options = OtgRasterizationOptions()
		otg_rasterization_options.page_size = cast(SizeF, image.size)
		save_options.vector_rasterization_options = otg_rasterization_options
		image.save(input_file_path + extension, save_options)


```

