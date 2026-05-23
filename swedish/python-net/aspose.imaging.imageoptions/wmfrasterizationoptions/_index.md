---
title: "WmfRasterizationOptions klass"
type: docs
weight: 380
url: /sv/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Initierar en ny instans av klassen [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger en bakgrundsfärg. |
| border_x | float | r/w | Hämtar eller anger gränsen X. |
| border_y | float | r/w | Hämtar eller anger gränsen Y. |
| center_drawing | bool | r/w | Hämtar eller anger ett värde som indikerar om ritning ska centreras. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger en förgrundsfärg. |
| page_height | float | r/w | Hämtar eller anger sidans höjd.<br/>            Om värdet är 0 bevaras källbildens bildförhållande. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Hämtar eller anger sidans storlek.<br/>            Om någon av [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensionerna är 0 bevaras källbildens bildförhållande. |
| page_width | float | r/w | Hämtar eller anger sidans bredd.<br/>            Om värdet är 0 bevaras källbildens bildförhållande. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Hämtar eller anger positioneringen. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Hämtar eller anger WMF-renderingsläget. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Hämtar eller anger tips för textrendering. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar ett nytt objekt som är en ytlig kopia av den aktuella instansen. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopierar detta till _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Initierar en ny instans av klassen [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/)

### Property: render_mode {#render_mode1}

Hämtar eller anger WMF-renderingsläget.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

Kopierar detta till _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

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

