---
title: "OtgRasterizationOptions klass"
type: docs
weight: 230
url: /sv/python-net/aspose.imaging.imageoptions/otgrasterizationoptions/
---

**Summary:** The Otg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OtgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions__1) | Initierar en ny instans av klassen OtgRasterizationOptions |
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
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Hämtar eller anger tips för textrendering. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar ett nytt objekt som är en ytlig kopia av den aktuella instansen. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopierar till. |


### Constructor: OtgRasterizationOptions() {#OtgRasterizationOptions__1}


```
 OtgRasterizationOptions() 
```

Initierar en ny instans av klassen OtgRasterizationOptions

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

