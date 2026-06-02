---
title: "Klasse JpegOptions"
type: docs
weight: 160
url: /de/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initialisiert eine neue Instanz der [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) Klasse. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initialisiert eine neue Instanz der [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Liest oder setzt Bits pro Kanal für verlustfreie JPEG-Bilder. Jetzt unterstützen wir von 2 bis 8 Bits pro Kanal. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden Sie es zum Speichern von Bildern. Es muss zusammen mit RGBColorProfile verwendet werden, um eine korrekte Farbumwandlung zu gewährleisten. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Liest oder setzt den Farbtyp für JPEG‑Bilder. |
| Kommentar | string | r/w | Liest oder setzt den JPEG‑Dateikommentar. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Liest oder setzt den Kompressionstyp. |
| default_memory_allocation_limit | int | r/w | Liest oder setzt das Standard‑Speicherzuweisungs‑Limit. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Lese oder setze den Exif‑Datencontainer. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| horizontal_sampling | System.Byte | r/w | Liest oder setzt die horizontalen Subsampling‑Werte für jede Komponente. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Liest oder setzt das JFIF. |
| jpeg_ls_allowed_lossy_error | int | r/w | Liest oder setzt die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Liest oder setzt den JPEG‑LS‑Interleavemodus. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Liest oder setzt die JPEG‑LS‑Voreinstellungsparameter. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| preblend_alpha_if_present | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Rot‑, Grün‑ und Blau‑Komponenten mit einer Hintergrundfarbe gemischt werden sollen, wenn ein Alphakanal vorhanden ist. |
| quality | int | r/w | Liest oder setzt die Bildqualität. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | Liest oder setzt die RD‑Optimierer‑Einstellungen. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Liest oder setzt die Auflösungseinheit. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden Sie es zum Speichern von Bildern. Es muss zusammen mit CMYKColorProfile verwendet werden, um eine korrekte Farbumwandlung zu gewährleisten. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Liest oder setzt den Sample‑Rundungsmodus, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | Die skalierte Qualität. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| vertical_sampling | System.Byte | r/w | Liest oder setzt die vertikalen Subsamplings für jede Komponente. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt eine memberweise Kopie dieser Instanz. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initialisiert eine neue Instanz der [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) Klasse.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initialisiert eine neue Instanz der [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | Die JPEG-Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt eine memberweise Kopie dieser Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Eine memberweise Kopie dieser Instanz. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Die Metadaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn die [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) Instanz unterstützt und/oder das [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) implementiert; andernfalls false. |


## **Examples**
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Lade ein vorhandenes GIF-Bild als Instanz der Image‑Klasse
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportiere in das BMP-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportiere in das JPEG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportiere in das PNG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportiere in das TIFF-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

