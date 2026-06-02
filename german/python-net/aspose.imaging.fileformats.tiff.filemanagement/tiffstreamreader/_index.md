---
title: "TiffStreamReader Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| length | int | r | Ermittelt die Länge des Readers. |
| throw_exceptions | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Ausnahmen bei fehlerhafter Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Liest ein Array von Byte-Werten aus dem Stream. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream. |
| [read_double(position)](#read_double_position_3) | Liest einen einzelnen Double-Wert aus dem Stream. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Liest ein Array von Double-Werten aus dem Stream. |
| [read_float(position)](#read_float_position_5) | Liest einen einzelnen Float-Wert aus dem Stream. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Liest ein Array von Float-Werten aus dem Stream. |
| [read_long(position)](#read_long_position_7) | Liest einen vorzeichenlosen Long-Wert aus dem Stream. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Liest ein Array von ulong-Werten aus dem Stream. |
| [read_rational(position)](#read_rational_position_9) | Liest einen einzelnen rationalen Zahlenwert aus dem Stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Liest ein Array von rationalen Werten aus dem Stream. |
| [read_s_byte(position)](#read_s_byte_position_11) | Liest vorzeichenbehaftete Byte-Daten aus dem Stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream. |
| [read_s_int(position)](#read_s_int_position_13) | Liest einen vorzeichenbehafteten Integer-Wert aus dem Stream. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Liest ein Array von vorzeichenbehafteten Integer-Werten aus dem Stream. |
| [read_s_rational(position)](#read_s_rational_position_15) | Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Liest ein Array von vorzeichenbehafteten rationalen Werten aus dem Stream. |
| [read_s_short(position)](#read_s_short_position_17) | Lese signed short-Wert aus dem Stream. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Liest ein Array von signed short-Werten aus dem Stream. |
| [read_u_int(position)](#read_u_int_position_19) | Lese unsigned integer-Wert aus dem Stream. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Liest ein Array von unsigned integer-Werten aus dem Stream. |
| [read_u_long(position)](#read_u_long_position_21) | Liest einen vorzeichenlosen Long-Wert aus dem Stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Liest ein Array von ulong-Werten aus dem Stream. |
| [read_u_short(position)](#read_u_short_position_23) | Lese unsigned short-Wert aus dem Stream. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Liest ein Array von unsigned integer-Werten aus dem Stream. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Konvertiert die zugrunde liegenden Daten in den Stream-Container. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die Byte-Array-Daten. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die Byte-Array-Daten. |
| start_index | int | Der Startindex in _data_. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die Byte-Array-Daten. |
| start_index | int | Der Startindex in _data_. |
| data_length | int | Länge der Daten. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Liest ein Array von Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| array | System.Byte | Das Array zum Befüllen. |
| array_index | int | Der Array-Index, um Werte zu setzen. |
| position | int | Die Stream-Position, von der gelesen wird. |
| count | int | Die zu lesende Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Array von Byte-Werten. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Das Array von unsigned byte-Werten. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Liest einen einzelnen Double-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der einzelne double-Wert. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Liest ein Array von Double-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Das Array von double-Werten. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Liest einen einzelnen Float-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der einzelne float-Wert. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Liest ein Array von Float-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Das Array von float-Werten. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Liest einen vorzeichenlosen Long-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein unsigned short-Wert. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Liest ein Array von ulong-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das ulong-Array. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Liest einen einzelnen rationalen Zahlenwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Die rationale Zahl. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Liest ein Array von rationalen Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Das Array rationaler Werte. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Liest vorzeichenbehaftete Byte-Daten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.SByte | Der signierte Byte-Wert. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.SByte | Das Array signierter Byte-Werte. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Liest einen vorzeichenbehafteten Integer-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein signierter Integer-Wert. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten Integer-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array signierter Integer-Werte. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Die signierte rationale Zahl. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten rationalen Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Das Array signierter rationaler Werte. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Lese signed short-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein signierter short-Wert. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Liest ein Array von signed short-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array signierter short-Werte. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Lese unsigned integer-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein unsignierter Integer-Wert. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Liest ein Array von unsigned integer-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array unsignierter Integer-Werte. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Liest einen vorzeichenlosen Long-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein unsigned short-Wert. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Liest ein Array von ulong-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das ulong-Array. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Lese unsigned short-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein unsigned short-Wert. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Liest ein Array von unsigned integer-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, von der gelesen wird. |
| count | int | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array unsignierter Integer-Werte. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Konvertiert die zugrunde liegenden Daten in den Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_position | int | Die Startposition, von der die Konvertierung ausgeführt wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) mit konvertierten Daten. |


