---
title: "Classe BigTiffReaderBE"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---

**Summary:** The big endian BigTiff stream writer.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReaderBE

**Inheritance:** TiffBigEndianStreamReader

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [BigTiffReaderBE(data)](#BigTiffReaderBE_data_1) | Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/). |
| [BigTiffReaderBE(data, start_index)](#BigTiffReaderBE_data_start_index_2) | Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/). |
| [BigTiffReaderBE(data, start_index, data_length)](#BigTiffReaderBE_data_start_index_data_length_3) | Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/). |
| [BigTiffReaderBE(stream_container)](#BigTiffReaderBE_stream_container_4) | Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| length | int | r | Ottiene la lunghezza del lettore. |
| throw_exceptions | bool | r/w | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione di dati errati (lettura o scrittura sullo stream). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Legge un array di valori byte dallo stream. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Legge un array di valori byte senza segno dallo stream. |
| [read_double(position)](#read_double_position_3) | Legge un singolo valore double dallo stream. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Legge un array di valori double dallo stream. |
| [read_float(position)](#read_float_position_5) | Legge un singolo valore float dallo stream. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Legge un array di valori float dallo stream. |
| [read_long(position)](#read_long_position_7) | Legge un valore unsigned long dallo stream. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Legge un array di valori ulong dallo stream. |
| [read_rational(position)](#read_rational_position_9) | Legge un singolo valore di numero razionale dallo stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Legge un array di valori razionali dallo stream. |
| [read_s_byte(position)](#read_s_byte_position_11) | Legge dati byte con segno dallo stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Legge un array di valori byte con segno dallo stream. |
| [read_s_int(position)](#read_s_int_position_13) | Legge un valore intero con segno dallo stream. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Legge un array di valori interi con segno dallo stream. |
| [read_s_rational(position)](#read_s_rational_position_15) | Legge un singolo valore di numero razionale con segno dallo stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Legge un array di valori razionali con segno dallo stream. |
| [read_s_short(position)](#read_s_short_position_17) | Leggi il valore short con segno dal flusso. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Legge un array di valori short con segno dal flusso. |
| [read_u_int(position)](#read_u_int_position_19) | Leggi il valore intero senza segno dal flusso. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Legge un array di valori interi senza segno dal flusso. |
| [read_u_long(position)](#read_u_long_position_21) | Legge un valore unsigned long dallo stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Legge un array di valori ulong dallo stream. |
| [read_u_short(position)](#read_u_short_position_23) | Leggi il valore short senza segno dal flusso. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Legge un array di valori interi senza segno dal flusso. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Converte i dati sottostanti nel contenitore del flusso. |


### Constructor: BigTiffReaderBE(data) {#BigTiffReaderBE_data_1}


```
 BigTiffReaderBE(data) 
```

Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | System.Byte | I dati dell'array di byte. |

### Constructor: BigTiffReaderBE(data, start_index) {#BigTiffReaderBE_data_start_index_2}


```
 BigTiffReaderBE(data, start_index) 
```

Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | System.Byte | I dati dell'array di byte. |
| start_index | int | L'indice di inizio in _data_. |

### Constructor: BigTiffReaderBE(data, start_index, data_length) {#BigTiffReaderBE_data_start_index_data_length_3}


```
 BigTiffReaderBE(data, start_index, data_length) 
```

Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | System.Byte | I dati dell'array di byte. |
| start_index | int | L'indice di inizio in _data_. |
| data_length | int | Lunghezza dei dati. |

### Constructor: BigTiffReaderBE(stream_container) {#BigTiffReaderBE_stream_container_4}


```
 BigTiffReaderBE(stream_container) 
```

Inizializza una nuova istanza della classe [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Legge un array di valori byte dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | System.Byte | L'array da riempire. |
| array_index | int | L'indice dell'array dove iniziare a inserire i valori. |
| position | int | La posizione del flusso da cui leggere. |
| count | int | Il conteggio degli elementi da leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'array di valori byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Legge un array di valori byte senza segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | L'array di valori byte senza segno. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Legge un singolo valore double dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | Il singolo valore double. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Legge un array di valori double dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] | L'array di valori double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Legge un singolo valore float dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | Il singolo valore float. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Legge un array di valori float dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float[] | L'array di valori float. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Legge un valore unsigned long dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore short senza segno. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Legge un array di valori ulong dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array ulong. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Legge un singolo valore di numero razionale dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Il numero razionale. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Legge un array di valori razionali dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | L'array di valori razionali. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Legge dati byte con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.SByte | Il valore del byte con segno. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Legge un array di valori byte con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.SByte | L'array di valori di byte con segno. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Legge un valore intero con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore intero con segno. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Legge un array di valori interi con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di valori interi con segno. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Legge un singolo valore di numero razionale con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Il numero razionale con segno. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Legge un array di valori razionali con segno dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | L'array di valori razionali con segno. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Leggi il valore short con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore short con segno. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Legge un array di valori short con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di valori short con segno. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Leggi il valore intero senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore intero senza segno. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Legge un array di valori interi senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di valori interi senza segno. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Legge un valore unsigned long dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore short senza segno. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Legge un array di valori ulong dallo stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array ulong. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Leggi il valore short senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore short senza segno. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Legge un array di valori interi senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui leggere. |
| count | int | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di valori interi senza segno. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Converte i dati sottostanti nel contenitore del flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_position | int | La posizione di inizio da cui avviare la conversione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) con dati convertiti. |


