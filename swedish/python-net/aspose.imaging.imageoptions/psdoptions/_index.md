---
title: "PsdOptions-klass"
type: docs
weight: 260
url: /sv/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initierar en ny instans av klassen [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_2) | Initierar en ny instans av klassen [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| channel_bits_count | int | r/w | Hämtar eller anger antalet bitar per färgkanal. |
| channels_count | int | r/w | Hämtar eller anger antalet färgkanaler. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Hämtar eller anger PSD-färgläget. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Hämtar eller anger PSD-komprimeringsmetoden. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Hämtar eller anger filformatets version. Den kan vara PSD eller PSB. |
| refresh_image_preview_data | bool | r/w | Hämtar eller anger ett värde som indikerar om [refresh image preview data] - alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare.<br/>            Observera att ritning av textlager till slutlig layout inte stöds för Compact Framework-plattformen |
| remove_global_text_engine_resource | bool | r/w | Hämtar eller anger ett värde som indikerar om - Ta bort den globala textmotormaterialet - Används för vissa textlager-psd-filer, i det enda fallet när de inte kan öppnas i Adobe Photoshop efter bearbetning (mest relaterat till saknade teckensnitt i textlager).<br/>            Efter att ha använt detta alternativ måste användaren göra följande i den öppnade Photoshop-filen: Meny "Text" -> "Process absent fonts". Efter den operationen kommer all text att visas igen.<br/>            Observera att denna operation kan orsaka vissa förändringar i den slutliga layouten. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Hämtar eller anger PSD-vektoriseringsalternativen. |
| version | int | r/w | Hämtar eller anger PSD-filens version. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämta eller ange XMP-datakontainer |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initierar en ny instans av klassen [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Initierar en ny instans av klassen [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Alternativen. |

### Property: color_mode {#color_mode1}

Hämtar eller anger PSD-färgläget.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Hämtar eller anger PSD-komprimeringsmetoden.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Skapar en instans av bildklassen och initierar den med en befintlig fil via filsökväg
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Skapa en instans av PsdOptions-klassen
	psdOptions = PsdOptions()
	#Ställ in CompressionMethod till RLE
	#Obs: En annan stödjande CompressionMethod är CompressionMethod.RAW [Ingen komprimering]
	psdOptions.compression_method = CompressionMethod.RLE
	#Ställ in ColorMode till GRAYSCALE
	#Obs: Andra stödda ColorModes är ColorModes.BITMAP och ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Spara bilden till disklokationen med de angivna PsdOptions-inställningarna
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

