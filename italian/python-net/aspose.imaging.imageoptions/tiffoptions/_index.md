---
title: "Classe TiffOptions"
type: docs
weight: 330
url: /it/python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Ottiene o imposta l'opzione di memorizzazione dell'alpha. Le opzioni diverse da [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            vengono utilizzate quando sono definiti più di 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| artist | string | r/w | Ottiene o imposta l'artista. |
| bits_per_pixel | int | r | Ottiene i bit per pixel. |
| bits_per_sample | int[] | r/w | Ottiene o imposta i bit per campione. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| color_map | int[] | r/w | Ottiene o imposta la mappa dei colori. |
| [compressed_quality](#compressed_quality1) | int | r/w | Ottiene o imposta la qualità dell'immagine compressa.<br/>            Utilizzata con la compressione Jpeg. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Ottiene o imposta la compressione. |
| copyright | string | r/w | Ottiene o imposta il copyright. |
| data_ora | string | r/w | Ottiene o imposta la data e l'ora. |
| default_memory_allocation_limit | int | r/w | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| disable_icc_export | bool | r/w | Ottiene o imposta un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato ai pixel di origine in anticipo). |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| document_name | string | r/w | Ottiene o imposta il nome del documento. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta i dati Exif. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Ottiene o imposta il puntatore a EXIF IFD. |
| extra_samples | int[] | r | Ottiene i valori dei campioni extra. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Ottiene o imposta le opzioni fax t4. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Ottiene o imposta lo standard del file TIFF. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| half_tone_hints | int[] | r/w | Ottiene o imposta i suggerimenti di mezzitoni. |
| descrizione_immagine | string | r/w | Ottiene o imposta la descrizione dell'immagine. |
| lunghezza_immagine | int | r/w | Ottiene o imposta la lunghezza dell'immagine. |
| larghezza_immagine | int | r/w | Ottiene o imposta la larghezza dell'immagine. |
| ink_names | string | r/w | Ottiene o imposta i nomi dell'inchiostro. |
| is_extra_samples_present | bool | r | Ottiene un valore che indica se i campioni extra sono presenti. |
| is_tiled | bool | r | Ottiene un valore che indica se l'immagine è suddivisa a tasselli. |
| is_valid | bool | r | Ottiene un valore che indica se le [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) sono state configurate correttamente. Utilizza il metodo Validate per trovare il motivo del fallimento. |
| keep_metadata | bool | r/w | Ottiene un valore che indica se mantenere i metadati originali dell'immagine durante l'esportazione. |
| max_sample_value | int[] | r/w | Ottiene o imposta il valore massimo del campione. |
| min_sample_value | int[] | r/w | Ottiene o imposta il valore minimo del campione. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Le opzioni multipagina |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Ottiene o imposta l'orientamento. |
| page_name | string | r/w | Ottiene o imposta il nome della pagina. |
| page_number | int[] | r/w | Ottiene o imposta il tag del numero di pagina. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Ottiene o imposta il valore fotometrico. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Ottiene o imposta la configurazione planare. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Ottiene o imposta il predittore per la compressione LZW. |
| premultiply_components | bool | r/w | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Ottiene o imposta l'unità di risoluzione. |
| rows_per_strip | int | r/w | Ottiene o imposta le righe per striscia. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Ottiene o imposta il formato del campione. |
| samples_per_pixel | int | r | Ottiene i campioni per pixel. Per modificare il valore di questa proprietà utilizza il setter della proprietà [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Ottiene o imposta il produttore dello scanner. |
| scanner_model | string | r/w | Ottiene o imposta il modello dello scanner. |
| smax_sample_value | int[] | r/w | Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (Byte, Short or Long type). |
| smin_sample_value | int[] | r/w | Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (Byte, Short or Long type). |
| software_type | string | r/w | Ottiene o imposta il tipo di software. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| strip_byte_counts | int[] | r/w | Ottiene o imposta i conteggi dei byte della striscia. |
| strip_offsets | int[] | r/w | Ottiene o imposta gli offset della striscia. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo sottofile. |
| tag_count | int | r | Ottiene il conteggio dei tag. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag. |
| target_printer | string | r/w | Ottiene o imposta la stampante di destinazione. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Ottiene o imposta la soglia. |
| tile_byte_counts | int[] | r/w | Ottiene o imposta i conteggi dei byte delle tile. |
| tile_length | int | r/w | Ottiene ot imposta la lunghezza della tile. |
| tile_offsets | int[] | r/w | Ottiene o imposta gli offset della tile. |
| tile_width | int | r/w | Ottiene ot imposta la larghezza della tile. |
| total_pages | int | r | Ottiene il numero totale di pagine. |
| valid_tag_count | int | r | Ottiene il conteggio dei tag validi. Questo non è il conteggio totale dei tag ma il numero di tag che possono essere conservati. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
| xp_author | string | r/w | Ottiene o imposta l'autore dell'immagine, utilizzato da Windows Explorer. |
| xp_comment | string | r/w | Ottiene o imposta il commento sull'immagine, utilizzato da Windows Explorer. |
| xp_keywords | string | r/w | Ottiene o imposta il soggetto dell'immagine, utilizzato da Windows Explorer. |
| xp_subject | string | r/w | Ottiene o imposta le informazioni sull'immagine, utilizzato da Windows Explorer. |
| xp_title | string | r/w | Ottiene o imposta le informazioni sull'immagine, utilizzato da Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la posizione x. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta i YCbCrCoefficients. |
| y_cb_cr_subsampling | int[] | r/w | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la posizione y. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione y. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Aggiunge un nuovo tag. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Aggiunge i tag. |
| [clone()](#clone__3) | Clona questa istanza. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian. |
| [create_with_options(options)](#create_with_options_options_5) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Ottiene l'istanza del tag per tipo. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Ottiene il conteggio dei tag validi. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Determina se il tag è presente nelle opzioni o meno. |
| [remove_tag(tag)](#remove_tag_tag_10) | Rimuove il tag. |
| [remove_tags(tags)](#remove_tags_tags_11) | Rimuove i tag. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| validate() | Convalida se le opzioni hanno una combinazione valida di tag |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Il formato file tiff previsto. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Il formato file tiff previsto. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordine dei byte del formato file tiff da utilizzare. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Le opzioni da copiare. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag con cui inizializzare le opzioni. |

### Property: compressed_quality {#compressed_quality1}

Ottiene o imposta la qualità dell'immagine compressa.<br/>            Utilizzata con la compressione Jpeg.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Aggiunge un nuovo tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Il tag da aggiungere. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Aggiunge i tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag da aggiungere. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Restituisce una copia profonda. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Il formato file tiff previsto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Le opzioni da copiare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Inizializza una nuova istanza della classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag con cui inizializzare le opzioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Ottiene l'istanza del tag per tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | La chiave del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Istanza del tag se esiste, altrimenti null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Ottiene il conteggio dei tag validi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag da convalidare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il conteggio dei tag validi. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Determina se il tag è presente nelle opzioni o meno.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | L'ID del tag da controllare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se il tag è presente; altrimenti, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Rimuove il tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Il tag da rimuovere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se rimosso con successo |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Rimuove i tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | I tag da rimuovere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | **True** se la dimensione della collezione di tag è cambiata. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea un'istanza di un flusso di file
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Crea un'istanza di TiffOptions e imposta le sue varie proprietà
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Imposta la sorgente per l'istanza di ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Crea un'istanza di Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		# Crea un'istanza della classe GraphicsPath
		graphics_path = GraphicsPath()
		# Crea un'istanza della classe Figure
		figure = Figure()
		# Aggiungi forme all'oggetto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# salva tutte le modifiche.
		image.save()


```

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

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Imposta il modello colore RGB.
	tiff_options.photometric = TiffPhotometrics.RGB
	# Imposta la compressione Jpeg.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# Imposta 8 bit per ogni componente colore.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

