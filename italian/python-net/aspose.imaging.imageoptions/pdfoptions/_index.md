---
title: "Classe PdfOptions"
type: docs
weight: 240
url: /it/python-net/aspose.imaging.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Inizializza una nuova istanza della classe [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Ottiene o imposta la dimensione della pagina. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| pdf_core_options | [PdfCoreOptions](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/) | r/w | Le opzioni principali del PDF |
| pdf_document_info | [PdfDocumentInfo](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfdocumentinfo/) | r/w | Ottiene o imposta i metadati per il documento. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| use_original_image_resolution | bool | r/w | Ottiene o imposta un valore che indica di utilizzare la risoluzione DPI originale dell'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Inizializza una nuova istanza della classe [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/).

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


