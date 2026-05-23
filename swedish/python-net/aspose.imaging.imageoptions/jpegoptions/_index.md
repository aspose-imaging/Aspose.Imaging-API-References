---
title: "JpegOptions-klass"
type: docs
weight: 160
url: /sv/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initierar en ny instans av klassen [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initierar en ny instans av klassen [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Hämtar eller anger bitar per kanal för förlustfri jpeg-bild. Nu stödjer vi från 2 till 8 bitar per kanal. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Destinations‑CMYK‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Hämtar eller anger färgtypen för jpeg‑bild. |
| kommentar | string | r/w | Hämtar eller anger jpeg‑filkommentaren. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Hämtar eller anger kompressionstypen. |
| default_memory_allocation_limit | int | r/w | Hämtar eller anger standardgränsen för minnesallokering. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Hämta eller ange Exif‑databehållare. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| horizontal_sampling | System.Byte | r/w | Hämtar eller anger de horisontella undersamplingarna för varje komponent. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Hämtar eller anger jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Hämtar eller anger JPEG-LS‑differensgränsen för nästan‑förlustfri kodning (NEAR‑parameter från JPEG-LS‑specifikationen). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Hämtar eller anger JPEG-LS‑interleavläge. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Hämtar eller anger JPEG-LS‑förinställda parametrar. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| preblend_alpha_if_present | bool | r/w | Hämtar eller anger ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| quality | int | r/w | Hämtar eller anger bildkvaliteten. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | Hämtar eller anger RD‑optimeringsinställningarna. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Hämtar eller anger upplösningsenheten. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Destinations‑RGB‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Hämtar eller anger provrundningsläget för att anpassa ett 8‑bitsvärde till ett n‑bitsvärde. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | Den skalade kvaliteten. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| vertical_sampling | System.Byte | r/w | Hämtar eller anger de vertikala delprovningarna för varje komponent. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initierar en ny instans av klassen [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initierar en ny instans av klassen [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | JPEG-alternativen. |

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
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Läs in en befintlig gif-bild som en instans av Image-klassen.
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportera till BMP-filformat med standardalternativen.
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportera till JPEG-filformat med standardalternativen.
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportera till PNG-filformat med standardalternativen.
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportera till TIFF-filformat med standardalternativen.
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

