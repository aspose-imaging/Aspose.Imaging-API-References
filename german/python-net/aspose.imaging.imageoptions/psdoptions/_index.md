---
title: "PsdOptions Klasse"
type: docs
weight: 260
url: /de/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initialisiert eine neue Instanz der [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) Klasse. |
| [PsdOptions(options)](#PsdOptions_options_2) | Initialisiert eine neue Instanz der [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| channel_bits_count | int | r/w | Liest oder setzt die Bitanzahl pro Farbkanal. |
| channels_count | int | r/w | Liest oder setzt die Anzahl der Farbkanäle. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Liest oder setzt den PSD-Farbmodus. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Liest oder setzt die PSD-Komprimierungsmethode. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif-Daten. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Liest oder setzt die Dateiformatversion. Sie kann PSD oder PSB sein. |
| refresh_image_preview_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] - Option verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren.<br/>            Bitte beachten Sie, dass das Zeichnen von Textebenen in das endgültige Layout für die Compact Framework-Plattform nicht unterstützt wird. |
| remove_global_text_engine_resource | bool | r/w | Liest oder setzt einen Wert, der angibt, ob - Die globale Text-Engine-Ressource entfernen - Wird für einige textschichtige PSD-Dateien verwendet, und zwar nur in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Textschichten).<br/>            Nach Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Datei folgendes ausführen: Menü "Text" -&gt; "Fehlende Schriften verarbeiten". Nach diesem Vorgang wird aller Text wieder angezeigt.<br/>            Bitte beachten Sie, dass dieser Vorgang einige Änderungen im endgültigen Layout verursachen kann. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Liest oder setzt die PSD-Vektorisierungsoptionen. |
| version | int | r/w | Liest oder setzt die PSD-Dateiversion. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Lese oder setze den XMP-Datencontainer |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt eine memberweise Kopie dieser Instanz. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initialisiert eine neue Instanz der [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) Klasse.

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Initialisiert eine neue Instanz der [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Die Optionen. |

### Property: color_mode {#color_mode1}

Liest oder setzt den PSD-Farbmodus.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Liest oder setzt die PSD-Komprimierungsmethode.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Erstellt eine Instanz der Bildklasse und initialisiert sie mit einer vorhandenen Datei über den Dateipfad
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Erstelle eine Instanz der PsdOptions-Klasse
	psdOptions = PsdOptions()
	#Setze die CompressionMethod auf RLE
	#Hinweis: Andere unterstützte CompressionMethod ist CompressionMethod.RAW [Keine Kompression]
	psdOptions.compression_method = CompressionMethod.RLE
	#Stellen Sie den ColorMode auf GRAYSCALE ein
	#Hinweis: Andere unterstützte ColorModes sind ColorModes.BITMAP und ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Speichern Sie das Bild am Speicherort mit den angegebenen PsdOptions-Einstellungen
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

