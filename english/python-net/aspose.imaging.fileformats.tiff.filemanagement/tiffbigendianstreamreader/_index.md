---
title: TiffBigEndianStreamReader Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/
---

**Summary:** The tiff stream for handling big endian tiff file format.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader

**Inheritance:** TiffStreamReader

**Aspose.Imaging Version:** 24.7.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffBigEndianStreamReader(data)](#TiffBigEndianStreamReader_data_1) | Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class. |
| [TiffBigEndianStreamReader(data, start_index)](#TiffBigEndianStreamReader_data_start_index_2) | Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class. |
| [TiffBigEndianStreamReader(data, start_index, data_length)](#TiffBigEndianStreamReader_data_start_index_data_length_3) | Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class. |
| [TiffBigEndianStreamReader(stream_container)](#TiffBigEndianStreamReader_stream_container_4) | Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| length | long | r | Gets the reader length. |
| throw_exceptions | bool | r/w | Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Reads an array of byte values from the stream. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Reads an array of unsigned byte values from the stream. |
| [read_double(position)](#read_double_position_3) | Read a single double value from the stream. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Reads an array of double values from the stream. |
| [read_float(position)](#read_float_position_5) | Read a single float value from the stream. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Reads an array of float values from the stream. |
| [read_long(position)](#read_long_position_7) | Read unsigned long value from the stream. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Reads an array of ulong values from the stream. |
| [read_rational(position)](#read_rational_position_9) | Read a single rational number value from the stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Reads an array of rational values from the stream. |
| [read_s_byte(position)](#read_s_byte_position_11) | Reads signed byte data from the stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Reads an array of signed byte values from the stream. |
| [read_s_int(position)](#read_s_int_position_13) | Read signed integer value from the stream. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Reads an array of signed integer values from the stream. |
| [read_s_rational(position)](#read_s_rational_position_15) | Read a single signed rational number value from the stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Reads an array of signed rational values from the stream. |
| [read_s_short(position)](#read_s_short_position_17) | Read signed short value from the stream. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Reads an array of signed short values from the stream. |
| [read_u_int(position)](#read_u_int_position_19) | Read unsigned integer value from the stream. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Reads an array of unsigned integer values from the stream. |
| [read_u_long(position)](#read_u_long_position_21) | Read unsigned long value from the stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Reads an array of ulong values from the stream. |
| [read_u_short(position)](#read_u_short_position_23) | Read unsigned short value from the stream. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Reads an array of unsigned integer values from the stream. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Converts the underlying data to the stream container. |


### Constructor: TiffBigEndianStreamReader(data) {#TiffBigEndianStreamReader_data_1}


```
 TiffBigEndianStreamReader(data) 
```

Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |

### Constructor: TiffBigEndianStreamReader(data, start_index) {#TiffBigEndianStreamReader_data_start_index_2}


```
 TiffBigEndianStreamReader(data, start_index) 
```

Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |
| start_index | int | The start index into _data_. |

### Constructor: TiffBigEndianStreamReader(data, start_index, data_length) {#TiffBigEndianStreamReader_data_start_index_data_length_3}


```
 TiffBigEndianStreamReader(data, start_index, data_length) 
```

Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The byte array data. |
| start_index | int | The start index into _data_. |
| data_length | int | Length of the data. |

### Constructor: TiffBigEndianStreamReader(stream_container) {#TiffBigEndianStreamReader_stream_container_4}


```
 TiffBigEndianStreamReader(stream_container) 
```

Initializes a new instance of the [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The stream container. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


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


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


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


### Method: read_double(position) {#read_double_position_3}


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


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


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


### Method: read_float(position) {#read_float_position_5}


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


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


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


### Method: read_long(position) {#read_long_position_7}


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


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


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


### Method: read_rational(position) {#read_rational_position_9}


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


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


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


### Method: read_s_byte(position) {#read_s_byte_position_11}


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


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


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


### Method: read_s_int(position) {#read_s_int_position_13}


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


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


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


### Method: read_s_rational(position) {#read_s_rational_position_15}


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


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


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


### Method: read_s_short(position) {#read_s_short_position_17}


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


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


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


### Method: read_u_int(position) {#read_u_int_position_19}


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


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


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


### Method: read_u_long(position) {#read_u_long_position_21}


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


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


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


### Method: read_u_short(position) {#read_u_short_position_23}


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


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


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


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


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


