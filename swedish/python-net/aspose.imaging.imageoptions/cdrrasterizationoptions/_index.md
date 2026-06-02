---
title: "CdrRasterizationOptions-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/
---

**Summary:** With the ability to perform CDR image rasterization and set scale factors<br/>            for both X and Y dimensions, this API provides precise control over the<br/>            transformation process. Whether scaling for specific output requirements<br/>            or converting vector graphics to raster formats, you can leverage this<br/>            API for efficient and customizable CDR vector to raster image conversion.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.CdrRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CdrRasterizationOptions()](#CdrRasterizationOptions__1) | Initierar en ny instans av klassen [CdrRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/). |
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
| scale_x | float | r/w | Hämtar eller anger skala x. |
| scale_y | float | r/w | Hämtar eller anger skala y. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Hämtar eller anger tips för textrendering. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar ett nytt objekt som är en ytlig kopia av den aktuella instansen. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopierar till. |


### Constructor: CdrRasterizationOptions() {#CdrRasterizationOptions__1}


```
 CdrRasterizationOptions() 
```

Initierar en ny instans av klassen [CdrRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/cdrrasterizationoptions/).

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

