---
title: "TiffSRationalType Classe"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---

**Summary:** The tiff signed rational type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffSRationalType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TiffSRationalType(tag_id)](#TiffSRationalType_tag_id_1) | Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe. |
| [TiffSRationalType(tag_id)](#TiffSRationalType_tag_id_2) | Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| count | int | r | Restituisce il conteggio degli elementi. |
| data_size | int | r | Restituisce la dimensione del valore del tag. |
| element_size | System.Byte | r | Restituisce la dimensione dell'elemento in byte. |
| id | int | r | Restituisce l'ID del tag come numero. |
| is_valid | bool | r | Restituisce un valore che indica se i dati del tag sono validi. Il tag valido contiene dati che possono essere conservati. Il tag non valido non può essere memorizzato. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Restituisce l'ID del tag. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Restituisce il tipo del tag. |
| valore | System.Object | r/w | Ottiene o imposta il valore contenuto da questo tipo di dati. |
| values | [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta i valori. |
| values_container | System.Array | r | Restituisce il contenitore dei valori. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe. |
| [deep_clone()](#deep_clone__4) | Esegue una clonazione profonda di questa istanza. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Ottiene la dimensione aggiuntiva del valore del tag in byte (nel caso in cui il tag non possa contenere l'intero valore del tag). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Ottiene la dimensione dei dati allineata a un confine di 4 byte (int) o 8 byte (long). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Legge i dati del tag. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Scrive i dati aggiuntivi del tag. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Scrive il valore del tag o l'offset aggiuntivo. |


### Constructor: TiffSRationalType(tag_id) {#TiffSRationalType_tag_id_1}


```
 TiffSRationalType(tag_id) 
```

Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | L'ID del tag. |

### Constructor: TiffSRationalType(tag_id) {#TiffSRationalType_tag_id_2}


```
 TiffSRationalType(tag_id) 
```

Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | int | L'ID del tag. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| obj | System.Object | Un oggetto da confrontare con questa istanza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un intero con segno a 32 bit che indica l'ordine relativo degli oggetti confrontati. Il valore restituito ha i seguenti significati:<br/>            Valore<br/>            Significato<br/>            Meno di zero<br/>            Questa istanza è minore di _obj_.<br/>            Zero<br/>            Questa istanza è uguale a _obj_.<br/>            Maggiore di zero<br/>            Questa istanza è maggiore di _obj_. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | L'ID del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Inizializza una nuova istanza di [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) classe.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | int | L'ID del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Esegue una clonazione profonda di questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Una clonazione profonda dell'istanza corrente. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Ottiene la dimensione aggiuntiva del valore del tag in byte (nel caso in cui il tag non possa contenere l'intero valore del tag).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Dimensione del valore del tag: 4 o 8 per BigTiff. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La dimensione aggiuntiva dei dati in byte. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Ottiene la dimensione dei dati allineata a un confine di 4 byte (int) o 8 byte (long).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Dimensione del valore del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La dimensione dei dati allineata in byte. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Legge i dati del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Il flusso di dati. |
| position | int | La posizione del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Il tag letto. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

Scrive i dati aggiuntivi del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Il flusso di dati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I byte effettivamente scritti. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Scrive il valore del tag o l'offset aggiuntivo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Il flusso di dati. |
| additional_data_offset | int | L'offset aggiuntivo dei dati. |

