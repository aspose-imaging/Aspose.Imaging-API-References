---
title: "DxfOptions Classe"
type: docs
weight: 80
url: /it/python-net/aspose.imaging.imageoptions/dxfoptions/
---

**Summary:** API for Drawing Interchange Format (DXF) vector image creation offers<br/>            tailored solutions for generating AutoCAD drawing files with precision and<br/>            flexibility. Designed specifically for working with text lines and Bezier<br/>            curves, developers can efficiently manipulate these elements, count Bezier<br/>            points, and convert curves into polylines for seamless exporting, ensuring<br/>            compatibility and fidelity in DXF vector images.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DxfOptions()](#DxfOptions__1) | Inizializza una nuova istanza della classe DxfOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bezier_point_count | System.Byte | r/w | Quanti punti generare durante la conversione delle curve Bezier in polilinee, minimo 4. Utilizzato quando [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) e [DxfOptions.convert_text_beziers](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) sono entrambi 	/// impostati a <c>true</c> |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| convert_text_beziers | bool | r/w | Funziona quando [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) è impostato a <c>true</c>. Se convertire le curve Bezier nei contorni del testo in polilinee multipunto. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| text_as_lines | bool | r/w | Se il testo deve essere esportato come contorni costituiti da polilinee (predefinito) o come entità TESTO modificabili di Autocad.<br/>            Se questa opzione è impostata |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonazione membro per membro di questa istanza. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: DxfOptions() {#DxfOptions__1}


```
 DxfOptions() 
```

Inizializza una nuova istanza della classe DxfOptions

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
### This example demonstrates export to Dxf format {#example_3}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DxfOptions
#Crea un'istanza di Image e inizializzala con un file immagine esistente dalla posizione su disco
with Image.load("input.svg") as image:
	options = DxfOptions()
	options.text_as_lines = True
	options.convert_text_beziers = True
	options.bezier_point_count = 20
	image.save("output.dxf", options)


```

