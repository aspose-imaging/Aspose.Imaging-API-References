---
title: BigTiffReaderBE Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---

The big endian BigTiff stream writer.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReaderBE

**Inheritance:** TiffBigEndianStreamReader

**Aspose.Imaging Version:** 23.6

The BigTiffReaderBE type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [BigTiffReaderBE(data)](#BigTiffReaderBE_data_0) | Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class. |
| [BigTiffReaderBE(stream_container)](#BigTiffReaderBE_stream_container_1) | Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class. |
| [BigTiffReaderBE(data, start_index)](#BigTiffReaderBE_data_start_index_2) | Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class. |
| [BigTiffReaderBE(data, start_index, data_length)](#BigTiffReaderBE_data_start_index_data_length_3) | Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| length | long | r | Gets the reader length. |
| throw_exceptions | bool | r/w | Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_4) | Reads an array of byte values from the stream. |
| [read_bytes(position, count)](#read_bytes_position_count_5) | Reads an array of unsigned byte values from the stream. |
| [read_double(position)](#read_double_position_6) | Read a single double value from the stream. |
| [read_double_array(position, count)](#read_double_array_position_count_7) | Reads an array of double values from the stream. |
| [read_float(position)](#read_float_position_8) | Read a single float value from the stream. |
| [read_float_array(position, count)](#read_float_array_position_count_9) | Reads an array of float values from the stream. |
| [read_rational(position)](#read_rational_position_10) | Read a single rational number value from the stream. |
| [read_s_rational(position)](#read_s_rational_position_11) | Read a single signed rational number value from the stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_12) | Reads an array of rational values from the stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_13) | Reads an array of signed rational values from the stream. |
| [read_s_byte(position)](#read_s_byte_position_14) | Reads signed byte data from the stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_15) | Reads an array of signed byte values from the stream. |
| [read_s_int(position)](#read_s_int_position_16) | Read signed integer value from the stream. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_17) | Reads an array of signed integer values from the stream. |
| [read_s_short(position)](#read_s_short_position_18) | Read signed short value from the stream. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_19) | Reads an array of signed short values from the stream. |
| [read_u_int(position)](#read_u_int_position_20) | Read unsigned integer value from the stream. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_21) | Reads an array of unsigned integer values from the stream. |
| [read_u_short(position)](#read_u_short_position_22) | Read unsigned short value from the stream. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_23) | Reads an array of unsigned integer values from the stream. |
| [read_long(position)](#read_long_position_24) | Read unsigned long value from the stream. |
| [read_long_array(position, count)](#read_long_array_position_count_25) | Reads an array of ulong values from the stream. |
| [read_u_long(position)](#read_u_long_position_26) | Read unsigned long value from the stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_27) | Reads an array of ulong values from the stream. |
| [to_stream_container(start_position)](#to_stream_container_start_position_28) | Converts the underlying data to the stream container. |

### BigTiffReaderBE(data) {#BigTiffReaderBE_data_0}


```
 BigTiffReaderBE(data) 
```

Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |

### BigTiffReaderBE(stream_container) {#BigTiffReaderBE_stream_container_1}


```
 BigTiffReaderBE(stream_container) 
```

Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The stream container. |

### BigTiffReaderBE(data, start_index) {#BigTiffReaderBE_data_start_index_2}


```
 BigTiffReaderBE(data, start_index) 
```

Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |
| start_index | int | The start index into <paramref name="data" />. |

### BigTiffReaderBE(data, start_index, data_length) {#BigTiffReaderBE_data_start_index_data_length_3}


```
 BigTiffReaderBE(data, start_index, data_length) 
```

Initializes a new instance of the [BigTiffReaderBE](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |
| start_index | int | The start index into <paramref name="data" />. |
| data_length | int | Length of the data. |

### read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_4}


```
 read_bytes(array, array_index, position, count) 
```

Reads an array of byte values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| array | byte | The array to fill. |
| array_index | int | The array index to start putting values to. |
| position | long | The stream position to read from. |
| count | long | The elements count to read. |

**Returns**

| Type | Description |
| :- | :- |
| long | The array of byte values. |


### read_bytes(position, count) {#read_bytes_position_count_5}


```
 read_bytes(position, count) 
```

Reads an array of unsigned byte values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The array of unsigned byte values. |


### read_double(position) {#read_double_position_6}


```
 read_double(position) 
```

Read a single double value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| double | The single double value. |


### read_double_array(position, count) {#read_double_array_position_count_7}


```
 read_double_array(position, count) 
```

Reads an array of double values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| double | The array of double values. |


### read_float(position) {#read_float_position_8}


```
 read_float(position) 
```

Read a single float value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| float | The single float value. |


### read_float_array(position, count) {#read_float_array_position_count_9}


```
 read_float_array(position, count) 
```

Reads an array of float values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| float | The array of float values. |


### read_rational(position) {#read_rational_position_10}


```
 read_rational(position) 
```

Read a single rational number value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | The rational number. |


### read_s_rational(position) {#read_s_rational_position_11}


```
 read_s_rational(position) 
```

Read a single signed rational number value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | The signed rational number. |


### read_rational_array(position, count) {#read_rational_array_position_count_12}


```
 read_rational_array(position, count) 
```

Reads an array of rational values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | The array of rational values. |


### read_s_rational_array(position, count) {#read_s_rational_array_position_count_13}


```
 read_s_rational_array(position, count) 
```

Reads an array of signed rational values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | The array of signed rational values. |


### read_s_byte(position) {#read_s_byte_position_14}


```
 read_s_byte(position) 
```

Reads signed byte data from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| sbyte | The signed byte value. |


### read_s_byte_array(position, count) {#read_s_byte_array_position_count_15}


```
 read_s_byte_array(position, count) 
```

Reads an array of signed byte values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| sbyte | The array of signed byte values. |


### read_s_int(position) {#read_s_int_position_16}


```
 read_s_int(position) 
```

Read signed integer value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| int | A signed integer value. |


### read_s_int_array(position, count) {#read_s_int_array_position_count_17}


```
 read_s_int_array(position, count) 
```

Reads an array of signed integer values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| int | The array of signed integer values. |


### read_s_short(position) {#read_s_short_position_18}


```
 read_s_short(position) 
```

Read signed short value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| short | A signed short value. |


### read_s_short_array(position, count) {#read_s_short_array_position_count_19}


```
 read_s_short_array(position, count) 
```

Reads an array of signed short values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| short | The array of signed short values. |


### read_u_int(position) {#read_u_int_position_20}


```
 read_u_int(position) 
```

Read unsigned integer value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| uint | An unsigned integer value. |


### read_u_int_array(position, count) {#read_u_int_array_position_count_21}


```
 read_u_int_array(position, count) 
```

Reads an array of unsigned integer values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| uint | The array of unsigned integer values. |


### read_u_short(position) {#read_u_short_position_22}


```
 read_u_short(position) 
```

Read unsigned short value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| ushort | An unsigned short value. |


### read_u_short_array(position, count) {#read_u_short_array_position_count_23}


```
 read_u_short_array(position, count) 
```

Reads an array of unsigned integer values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| ushort | The array of unsigned integer values. |


### read_long(position) {#read_long_position_24}


```
 read_long(position) 
```

Read unsigned long value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| long | An unsigned short value. |


### read_long_array(position, count) {#read_long_array_position_count_25}


```
 read_long_array(position, count) 
```

Reads an array of ulong values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| long | The ulong array. |


### read_u_long(position) {#read_u_long_position_26}


```
 read_u_long(position) 
```

Read unsigned long value from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |

**Returns**

| Type | Description |
| :- | :- |
| ulong | An unsigned short value. |


### read_u_long_array(position, count) {#read_u_long_array_position_count_27}


```
 read_u_long_array(position, count) 
```

Reads an array of ulong values from the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns**

| Type | Description |
| :- | :- |
| ulong | The ulong array. |


### to_stream_container(start_position) {#to_stream_container_start_position_28}


```
 to_stream_container(start_position) 
```

Converts the underlying data to the stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_position | long | The start position to start conversion from. |

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) with converted data. |


