---
title: "Classe PsdOptions"
type: docs
weight: 260
url: /it/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Inizializza una nuova istanza della classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_2) | Inizializza una nuova istanza della classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| channel_bits_count | int | r/w | Ottiene o imposta il conteggio dei bit per canale colore. |
| channels_count | int | r/w | Ottiene o imposta il conteggio dei canali colore. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Ottiene o imposta la modalità colore PSD. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Ottiene o imposta il metodo di compressione PSD. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Ottiene o imposta la versione del formato file. Può essere PSD o PSB. |
| refresh_image_preview_data | bool | r/w | Ottiene o imposta un valore che indica se [refresh image preview data] - opzione usata per massimizzare la compatibilità con altri visualizzatori di immagini PSD.<br/>            Si prega di notare che il disegno dei livelli di testo nel layout finale non è supportato per la piattaforma Compact Framework |
| remove_global_text_engine_resource | bool | r/w | Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file PSD a più livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti).<br/>            Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu "Text" -&gt; "Process absent fonts". Dopo tale operazione tutto il testo riapparirà.<br/>            Si prega di notare che questa operazione può causare alcune modifiche al layout finale. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Ottiene o imposta le opzioni di vettorizzazione PSD. |
| versione | int | r/w | Ottiene o imposta la versione del file PSD. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottieni o imposta il contenitore dati XMP |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Inizializza una nuova istanza della classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Inizializza una nuova istanza della classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Le opzioni. |

### Property: color_mode {#color_mode1}

Ottiene o imposta la modalità colore PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Ottiene o imposta il metodo di compressione PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Crea un'istanza della classe immagine e la inizializza con un file esistente tramite percorso del file
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Crea un'istanza della classe PsdOptions
	psdOptions = PsdOptions()
	#Imposta CompressionMethod come RLE
	#Nota: Un altro CompressionMethod supportato è CompressionMethod.RAW [Nessuna compressione]
	psdOptions.compression_method = CompressionMethod.RLE
	#Imposta il ColorMode su GRAYSCALE
	#Nota: altri ColorModes supportati sono ColorModes.BITMAP e ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Salva l'immagine nella posizione su disco con le impostazioni PsdOptions fornite
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

