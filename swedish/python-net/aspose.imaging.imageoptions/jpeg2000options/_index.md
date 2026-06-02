---
title: "Jpeg2000Options klass"
type: docs
weight: 150
url: /sv/python-net/aspose.imaging.imageoptions/jpeg2000options/
---

**Summary:** Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology<br/>            for coding lossless content. Benefit from support for various codecs, including<br/>            irreversible and lossless compression, as well as XMP metadata containers, ensuring<br/>            versatility and high-quality image creation tailored to your needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Initierar en ny instans av klassen [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Initierar en ny instans av klassen [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [codec](#codec1) | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | Hämtar eller anger JPEG2000‑kodaren |
| kommentarer | string[] | r/w | Hämtar eller anger Jpeg‑kommentarmarkörer. |
| compression_ratios | int[] | r/w | Hämtar eller anger arrayen av komprimeringsförhållanden.<br/>            Olika komprimeringsförhållanden för på varandra följande lager.<br/>            Den angivna hastigheten för varje kvalitetsnivå är den önskade<br/>            komprimeringsfaktorn.<br/>            Minskande förhållanden krävs. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| [irreversible](#irreversible2) | bool | r/w | Hämtar eller anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3‑kompression (standard) ska användas. |
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


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Initierar en ny instans av klassen [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/)

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Initierar en ny instans av klassen [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/)

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | Jpeg2000‑filformatalternativen att kopiera inställningar från. |

### Property: codec {#codec1}

Hämtar eller anger JPEG2000‑kodaren

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Property: irreversible {#irreversible2}

Hämtar eller anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3‑kompression (standard) ska användas.

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


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
### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# Använd den irreversibla diskreta vågtransformen 9‑7
create_options.irreversible = True
# JP2 är "container"-formatet för JPEG 2000-kodströmmar.
# J2K är rå komprimerad data, utan en omslag.
create_options.codec = Jpeg2000Codec.J2K
# Skapa en JPEG2000-bild på 100×100 px.
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Fyll hela bilden med rött.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# Spara till en fil
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# Skapa en PNG-bild på 100x100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Fyll hela bilden med rött.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# Använd den irreversibla diskreta vågtransformen 9‑7
	save_options.irreversible = True
	# JP2 är "container"-formatet för JPEG 2000-kodströmmar.
	# J2K är rå komprimerad data, utan en omslag.
	save_options.codec = Jpeg2000Codec.J2K
	# Spara till en fil
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

