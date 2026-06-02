---
title: "Html5CanvasOptions klass"
type: docs
weight: 130
url: /sv/python-net/aspose.imaging.imageoptions/html5canvasoptions/
---

**Summary:** Create HTML5 Canvas files effortlessly with our API, allowing you to seamlessly<br/>            combine elements like forms, text, images, animations, and links. Benefit from<br/>            robust features including tag identifier and encoding settings support,<br/>            ensuring optimal performance and customization for your web projects.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Html5CanvasOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Html5CanvasOptions()](#Html5CanvasOptions__1) | Initierar en ny instans av klassen [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| canvas_tag_id | string | r/w | Hämtar eller anger identifieraren för canvas-taggen. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| encoding | string | r/w | Hämtar eller anger kodningen. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| full_html_page | bool | r/w | Hämtar eller anger ett värde som indikerar om hela HTML-sidan ska genereras. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: Html5CanvasOptions() {#Html5CanvasOptions__1}


```
 Html5CanvasOptions() 
```

Initierar en ny instans av klassen [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/).

### Method: clone() {#clone__1}


```
 clone() 
```

Skapar en medlemsvis klon av detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | En medlemsvis klon av detta objekt. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Metadata. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant, om [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/)‑instansen stöder och/eller implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑instansen; annars falskt. |


## **Examples**
### Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image. {#example_199}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	export_options = Html5CanvasOptions()
	export_options.vector_rasterization_options = SvgRasterizationOptions()
	image.save("Canvas.html", export_options)


```

### You can embed more than one Canvas image within HTML page or update already exsiting page. In order to do that you need to export only the Canvas tag. {#example_200}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	options = Html5CanvasOptions()
	options.vector_rasterization_options = SvgRasterizationOptions()
	options.full_html_page = False
	image.save("Canvas.html", options)


```

