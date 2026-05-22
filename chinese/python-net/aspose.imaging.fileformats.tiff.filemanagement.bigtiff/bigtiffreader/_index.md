---
title: "BigTiffReader 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

**Summary:** The little endian BigTiff reader.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [BigTiffReader(data)](#BigTiffReader_data_1) | 初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。 |
| [BigTiffReader(data, start_index)](#BigTiffReader_data_start_index_2) | 初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。 |
| [BigTiffReader(data, start_index, data_length)](#BigTiffReader_data_start_index_data_length_3) | 初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。 |
| [BigTiffReader(stream_container)](#BigTiffReader_stream_container_4) | 初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| length | int | r | 获取读取器的长度。 |
| throw_exceptions | bool | r/w | 获取或设置一个值，指示在错误的数据处理（读取或写入流）时是否抛出异常。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | 从流中读取字节值数组。 |
| [read_bytes(position, count)](#read_bytes_position_count_2) | 从流中读取无符号字节值数组。 |
| [read_double(position)](#read_double_position_3) | 从流中读取单个 double 值。 |
| [read_double_array(position, count)](#read_double_array_position_count_4) | 从流中读取 double 值数组。 |
| [read_float(position)](#read_float_position_5) | 从流中读取单个 float 值。 |
| [read_float_array(position, count)](#read_float_array_position_count_6) | 从流中读取 float 值数组。 |
| [read_long(position)](#read_long_position_7) | 从流中读取无符号 long 值。 |
| [read_long_array(position, count)](#read_long_array_position_count_8) | 从流中读取 ulong 值数组。 |
| [read_rational(position)](#read_rational_position_9) | 从流中读取单个有理数值。 |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | 从流中读取有理数值数组。 |
| [read_s_byte(position)](#read_s_byte_position_11) | 从流中读取有符号字节数据。 |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | 从流中读取有符号字节值数组。 |
| [read_s_int(position)](#read_s_int_position_13) | 从流中读取有符号整数值。 |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | 从流中读取有符号整数值数组。 |
| [read_s_rational(position)](#read_s_rational_position_15) | 从流中读取单个有符号有理数值。 |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | 从流中读取有符号有理数值数组。 |
| [read_s_short(position)](#read_s_short_position_17) | 从流中读取有符号短整数值。 |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | 从流中读取有符号短整数值数组。 |
| [read_u_int(position)](#read_u_int_position_19) | 从流中读取无符号整数值。 |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | 从流中读取无符号整数值数组。 |
| [read_u_long(position)](#read_u_long_position_21) | 从流中读取无符号 long 值。 |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | 从流中读取 ulong 值数组。 |
| [read_u_short(position)](#read_u_short_position_23) | 从流中读取无符号短整数值。 |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | 从流中读取无符号整数值数组。 |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | 将底层数据转换为流容器。 |


### Constructor: BigTiffReader(data) {#BigTiffReader_data_1}


```
 BigTiffReader(data) 
```

初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 数据 | System.Byte | 字节数组数据。 |

### Constructor: BigTiffReader(data, start_index) {#BigTiffReader_data_start_index_2}


```
 BigTiffReader(data, start_index) 
```

初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 数据 | System.Byte | 字节数组数据。 |
| start_index | int | 在 _data_ 中的起始索引。 |

### Constructor: BigTiffReader(data, start_index, data_length) {#BigTiffReader_data_start_index_data_length_3}


```
 BigTiffReader(data, start_index, data_length) 
```

初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 数据 | System.Byte | 字节数组数据。 |
| start_index | int | 在 _data_ 中的起始索引。 |
| data_length | int | 数据的长度。 |

### Constructor: BigTiffReader(stream_container) {#BigTiffReader_stream_container_4}


```
 BigTiffReader(stream_container) 
```

初始化 [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

从流中读取字节值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| array | System.Byte | 要填充的数组。 |
| array_index | int | 用于开始放置值的数组索引。 |
| position | int | 要读取的流位置。 |
| count | int | 要读取的元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 字节值数组。 |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

从流中读取无符号字节值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 无符号字节值数组。 |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

从流中读取单个 double 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| float | 单个 double 值。 |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

从流中读取 double 值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| float[] | double 值数组。 |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

从流中读取单个 float 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| float | 单个 float 值。 |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

从流中读取 float 值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| float[] | float 值数组。 |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

从流中读取无符号 long 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个无符号短整数值。 |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

从流中读取 ulong 值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该 ulong 数组。 |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

从流中读取单个有理数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | 该有理数。 |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

从流中读取有理数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | 该有理值数组。 |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

从流中读取有符号字节数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| System.SByte | 该有符号字节值。 |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

从流中读取有符号字节值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| System.SByte | 该有符号字节值数组。 |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

从流中读取有符号整数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个有符号整数值。 |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

从流中读取有符号整数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该有符号整数值数组。 |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

从流中读取单个有符号有理数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 该有符号有理数。 |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

从流中读取有符号有理数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 该有符号有理值数组。 |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

从流中读取有符号短整数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个有符号短整数值。 |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

从流中读取有符号短整数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该有符号短整数值数组。 |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

从流中读取无符号整数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个无符号整数值。 |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

从流中读取无符号整数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该无符号整数值数组。 |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

从流中读取无符号 long 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个无符号短整数值。 |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

从流中读取 ulong 值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该 ulong 数组。 |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

从流中读取无符号短整数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个无符号短整数值。 |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

从流中读取无符号整数值数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 读取的位置。 |
| count | int | 元素计数。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 该无符号整数值数组。 |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

将底层数据转换为流容器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| start_position | int | 该用于开始转换的起始位置。 |

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 带有转换后数据的 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/)。 |


