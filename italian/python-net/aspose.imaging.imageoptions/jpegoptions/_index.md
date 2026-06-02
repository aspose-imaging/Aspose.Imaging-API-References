---
title: "Classe JpegOptions"
type: docs
weight: 160
url: /it/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Inizializza una nuova istanza della classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Inizializza una nuova istanza della classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Ottiene o imposta i bit per canale per un'immagine jpeg senza perdita. Ora supportiamo da 2 a 8 bit per canale. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. Usare per salvare le immagini. Deve essere in coppia con RGBColorProfile per una corretta conversione del colore. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| commento | string | r/w | Ottiene o imposta il commento del file jpeg. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Ottiene o imposta il tipo di compressione. |
| default_memory_allocation_limit | int | r/w | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Ottieni o imposta il contenitore dei dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| horizontal_sampling | System.Byte | r/w | Ottiene o imposta i campionamenti orizzontali per ciascun componente. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Ottiene o imposta il jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Ottiene o imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Ottiene o imposta la modalità di interlacciamento JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Ottiene o imposta i parametri predefiniti JPEG-LS. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| preblend_alpha_if_present | bool | r/w | Ottiene o imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| quality | int | r/w | Ottiene o imposta la qualità dell'immagine. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | Ottiene o imposta le impostazioni dell'ottimizzatore RD. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Ottiene o imposta l'unità di risoluzione. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. Usare per salvare le immagini. Deve essere in coppia con CMYKColorProfile per una corretta conversione del colore. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | La qualità scalata. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| vertical_sampling | System.Byte | r/w | Ottiene o imposta i sottocampionamenti verticali per ogni componente. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Inizializza una nuova istanza della classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Inizializza una nuova istanza della classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | Le opzioni JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Crea una clonazione membro per membro di questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Una clonazione membro per membro di questa istanza. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | I metadati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | True, se l'istanza [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) supporta e/o implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); altrimenti, false. |


## **Examples**
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Carica un'immagine gif esistente come istanza della classe Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# Esporta nel formato file BMP utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Esporta nel formato file JPEG utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Esporta nel formato file PNG utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.png"), PngOptions())
	# Esporta nel formato file TIFF utilizzando le opzioni predefinite
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

