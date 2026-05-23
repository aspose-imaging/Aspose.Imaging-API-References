---
title: "TiffBigEndianStreamReader Klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/
---

**Summary:** The tiff stream for handling big endian tiff file format.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffBigEndianStreamReader(data)](#TiffBigEndianStreamReader_data_1) | Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass. |
| [TiffBigEndianStreamReader(data, start_index)](#TiffBigEndianStreamReader_data_start_index_2) | Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass. |
| [TiffBigEndianStreamReader(data, start_index, data_length)](#TiffBigEndianStreamReader_data_start_index_data_length_3) | Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass. |
| [TiffBigEndianStreamReader(stream_container)](#TiffBigEndianStreamReader_stream_container_4) | Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| length | int | r | Hämtar läsarens längd. |
| throw_exceptions | bool | r/w | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till ström). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Läser en array av bytevärden från strömmen. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Läser en array av osignerade bytevärden från strömmen. |
| [read_double(position)](#read_double_position_3) | Läser ett enskilt double‑värde från strömmen. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Läser en array av double‑värden från strömmen. |
| [read_float(position)](#read_float_position_5) | Läser ett enskilt float‑värde från strömmen. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Läser en array av float‑värden från strömmen. |
| [read_long(position)](#read_long_position_7) | Läser ett osignerat long‑värde från strömmen. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Läser en array av ulong‑värden från strömmen. |
| [read_rational(position)](#read_rational_position_9) | Läser ett enskilt rationellt talvärde från strömmen. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Läser en array av rationella talvärden från strömmen. |
| [read_s_byte(position)](#read_s_byte_position_11) | Läser signerad byte‑data från strömmen. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Läser en array av signerade bytevärden från strömmen. |
| [read_s_int(position)](#read_s_int_position_13) | Läser ett signerat heltalsvärde från strömmen. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Läser en array av signerade heltalsvärden från strömmen. |
| [read_s_rational(position)](#read_s_rational_position_15) | Läser ett enskilt signerat rationellt talvärde från strömmen. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Läser en array av signerade rationella talvärden från strömmen. |
| [read_s_short(position)](#read_s_short_position_17) | Läs ett signerat short‑värde från strömmen. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Läser en array av signerade short‑värden från strömmen. |
| [read_u_int(position)](#read_u_int_position_19) | Läs ett osignerat integer‑värde från strömmen. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Läser en array av osignerade integer‑värden från strömmen. |
| [read_u_long(position)](#read_u_long_position_21) | Läser ett osignerat long‑värde från strömmen. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Läser en array av ulong‑värden från strömmen. |
| [read_u_short(position)](#read_u_short_position_23) | Läs ett osignerat short‑värde från strömmen. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Läser en array av osignerade integer‑värden från strömmen. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Konverterar den underliggande datan till strömbehållaren. |


### Constructor: TiffBigEndianStreamReader(data) {#TiffBigEndianStreamReader_data_1}


```
 TiffBigEndianStreamReader(data) 
```

Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | System.Byte | Byte‑array‑datan. |

### Constructor: TiffBigEndianStreamReader(data, start_index) {#TiffBigEndianStreamReader_data_start_index_2}


```
 TiffBigEndianStreamReader(data, start_index) 
```

Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | System.Byte | Byte‑array‑datan. |
| start_index | int | Startindexet i _data_. |

### Constructor: TiffBigEndianStreamReader(data, start_index, data_length) {#TiffBigEndianStreamReader_data_start_index_data_length_3}


```
 TiffBigEndianStreamReader(data, start_index, data_length) 
```

Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | System.Byte | Byte‑array‑datan. |
| start_index | int | Startindexet i _data_. |
| data_length | int | Längden på datan. |

### Constructor: TiffBigEndianStreamReader(stream_container) {#TiffBigEndianStreamReader_stream_container_4}


```
 TiffBigEndianStreamReader(stream_container) 
```

Initierar en ny instans av [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Läser en array av bytevärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| array | System.Byte | Arrayen att fylla. |
| array_index | int | Array‑indexet att börja placera värden i. |
| position | int | Strömmens position att läsa från. |
| count | int | Antalet element att läsa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Arrayen av byte‑värden. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Läser en array av osignerade bytevärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Arrayen av osignerade byte‑värden. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Läser ett enskilt double‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Det enkla double‑värdet. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Läser en array av double‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | Arrayen av double‑värden. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Läser ett enskilt float‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Det enkla float‑värdet. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Läser en array av float‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | Arrayen av float‑värden. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Läser ett osignerat long‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett osignerat short‑värde. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Läser en array av ulong‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Den ulong‑arrayen. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Läser ett enskilt rationellt talvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Det rationella talet. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Läser en array av rationella talvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Arrayen av rationella värden. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Läser signerad byte‑data från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.SByte | Det signerade byte‑värdet. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Läser en array av signerade bytevärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.SByte | Arrayen av signerade byte‑värden. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Läser ett signerat heltalsvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett signerat heltalsvärde. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Läser en array av signerade heltalsvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Arrayen av signerade heltalsvärden. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Läser ett enskilt signerat rationellt talvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Det signerade rationella talet. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Läser en array av signerade rationella talvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Arrayen av signerade rationella värden. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Läs ett signerat short‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett signerat short‑värde. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Läser en array av signerade short‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Arrayen av signerade short‑värden. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Läs ett osignerat integer‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett osignerat heltalsvärde. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Läser en array av osignerade integer‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Arrayen av osignerade heltalsvärden. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Läser ett osignerat long‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett osignerat short‑värde. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Läser en array av ulong‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Den ulong‑arrayen. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Läs ett osignerat short‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett osignerat short‑värde. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Läser en array av osignerade integer‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att läsa från. |
| count | int | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Arrayen av osignerade heltalsvärden. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Konverterar den underliggande datan till strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_position | int | Startpositionen att börja konverteringen från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Den [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) med konverterad data. |


