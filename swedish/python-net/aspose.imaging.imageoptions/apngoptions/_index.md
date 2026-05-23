---
title: "ApngOptions-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file format<br/>            creation is a dynamic tool for developers seeking to generate captivating<br/>            animated images. With customizable options such as frame duration and the<br/>            number of times to loop, this API allows for fine-tuning animated content<br/>            according to specific needs. Whether creating engaging web graphics or<br/>            interactive visuals, you can leverage this API to seamlessly incorporate<br/>            APNG images with precise control over animation parameters.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, PngOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | Initierar en ny instans av klassen [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Standardkomprimeringsnivån. |
| bit_depth | System.Byte | r/w | Hämtar eller anger bitdjupsvärdena i intervallet 1, 2, 4, 8, 16.<br/>            <br/><br/>            Observera följande begränsningar:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Hämtar eller anger färgens typ. |
| compression_level | int | r/w | Hämtar eller anger komprimeringsnivån för [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [default_frame_time](#default_frame_time1) | int | r/w | Hämtar eller anger standardramens varaktighet. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Hämtar eller anger filtertypen som används under sparprocessen för png‑filen. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| [num_plays](#num_plays2) | int | r/w | Hämtar eller anger antalet gånger animationen ska loopas.<br/>            0 indikerar oändlig loopning. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Hämtar eller anger komprimeringsnivån för [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| progressive | bool | r/w | Hämtar eller anger ett värde som indikerar om en [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) är progressiv. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

Initierar en ny instans av klassen [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/).

### Property: default_frame_time {#default_frame_time1}

Hämtar eller anger standardramens varaktighet.

**See also:**

**[Example # 1](#example_198)**: The following example shows how to export apng APNG file format from other no...


### Property: num_plays {#num_plays2}

Hämtar eller anger antalet gånger animationen ska loopas.<br/>            0 indikerar oändlig loopning.

**See also:**

**[Example # 1](#example_197)**: The following example shows how to export to APNG file format.


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
| bool | Sant om _metadata_ inte är null och [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/)‑instansen <br/>            stöder och/eller implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑instansen; annars falskt. |


## **Examples**
### The following example shows how to export to APNG file format. {#example_197}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# Exportera till APNG-animation med obegränsade animationscykler som standard
	image.save("Animation1.webp.png", ApngOptions())
	# Ställa in animationscykler
	obj_init = ApngOptions()
	# 5 cykler
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_198}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# Ställa in standardramens varaktighet
	obj_init = ApngOptions()
	# 500 ms
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 ms
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

