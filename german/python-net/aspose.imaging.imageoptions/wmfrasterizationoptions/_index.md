---
title: "WmfRasterizationOptions Klasse"
type: docs
weight: 380
url: /de/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Initialisiert eine neue Instanz der [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) Klasse. |
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
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Liest oder setzt den WMF-Rendermodus. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Liest oder setzt den Glättungsmodus. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Liest oder setzt den Hinweis zur Textdarstellung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine flache Kopie der aktuellen Instanz ist. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopiert dies nach _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Initialisiert eine neue Instanz der [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) Klasse.

### Property: render_mode {#render_mode1}

Liest oder setzt den WMF-Rendermodus.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

Kopiert dies nach _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

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

