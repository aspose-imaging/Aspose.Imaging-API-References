---
title: "Classe IcoOptions"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.imageoptions/icooptions/
---

**Summary:** Create custom ICO image files for application icons effortlessly with our API,<br/>            empowering you to represent your software seamlessly. Our API supports PNG and<br/>            BMP image frames with various bits per pixel values, ensuring versatility and<br/>            compatibility for your icon creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [IcoOptions()](#IcoOptions__1) | Inizializza una nuova istanza della classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) con il formato del frame ICO uguale a Png e<br/>            bitsPerPixel uguale a 32. |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_2) | Inizializza una nuova istanza della classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Ottiene o imposta il valore bits-per-pixel. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r/w | Ottiene o imposta il formato del frame ICO. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: IcoOptions() {#IcoOptions__1}


```
 IcoOptions() 
```

Inizializza una nuova istanza della classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) con il formato del frame ICO uguale a Png e<br/>            bitsPerPixel uguale a 32.

### Constructor: IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_2}


```
 IcoOptions(format, bits_per_pixel) 
```

Inizializza una nuova istanza della classe [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Il formato del frame ICO.<br/>            Nota che l'immagine ICO supporta solo le immagini [FileFormat.PNG](/imaging/python-net/aspose.imaging/fileformat/) e [FileFormat.BMP](/imaging/python-net/aspose.imaging/fileformat/) come voci. |
| bits_per_pixel | int | Il valore bits-per-pixel. |

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


