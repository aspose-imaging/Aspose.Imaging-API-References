---
title: "TiffLong8Type 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---

**Summary:** The Tiff unsigned 64-bit type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffLong8Type

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TiffLong8Type(tag_id)](#TiffLong8Type_tag_id_1) | 初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。 |
| [TiffLong8Type(tag_id)](#TiffLong8Type_tag_id_2) | 初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取元素的计数。 |
| data_size | int | r | 获取标签值的大小。 |
| element_size | System.Byte | r | 获取元素的大小。 |
| id | int | r | 获取标签 ID（数字）。 |
| is_valid | bool | r | 获取一个值，指示标签数据是否有效。有效的标签包含可保留的数据。无效的标签无法存储。 |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | 获取标签 ID。 |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | 获取标签类型。 |
| value | System.Object | r/w | 获取或设置此数据类型包含的值。 |
| values | int[] | r/w | 获取或设置这些值。 |
| values_container | System.Array | r | 获取值容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于、跟随还是与另一个对象处于相同位置。 |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | 初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。 |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | 初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。 |
| [deep_clone()](#deep_clone__4) | 对该实例执行深度克隆。 |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | 获取附加标签值的大小（以字节为单位）（如果标签无法容纳完整的标签值）。 |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | 获取按4字节（int）或8字节（long）边界对齐的数据大小。 |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | 读取标签数据。 |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | 写入附加标签数据。 |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | 写入标签值或附加偏移量。 |


### Constructor: TiffLong8Type(tag_id) {#TiffLong8Type_tag_id_1}


```
 TiffLong8Type(tag_id) 
```

初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | int | 标签 ID。 |

### Constructor: TiffLong8Type(tag_id) {#TiffLong8Type_tag_id_2}


```
 TiffLong8Type(tag_id) 
```

初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 标签 ID。 |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于、跟随还是与另一个对象处于相同位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| obj | System.Object | 用于与此实例比较的对象。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 一个 32 位有符号整数，指示被比较对象的相对顺序。返回值具有以下含义：<br/>            值<br/>            含义<br/>            小于零<br/>            此实例小于 _obj_。<br/>            零<br/>            此实例等于 _obj_。<br/>            大于零<br/>            此实例大于 _obj_。 |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 标签 ID。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

初始化 [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | int | 标签 ID。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffLong8Type](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

对该实例执行深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 当前实例的深度克隆。 |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

获取附加标签值的大小（以字节为单位）（如果标签无法容纳完整的标签值）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | 标签值的大小：BigTiff 为 4 或 8。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 附加数据的大小（字节）。 |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

获取按4字节（int）或8字节（long）边界对齐的数据大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | 标签值的大小。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 对齐后的数据大小（字节）。 |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

读取标签数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | 数据流。 |
| position | int | 标签位置。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 读取的标签。 |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

写入附加标签数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | 数据流。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 实际写入的字节数。 |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

写入标签值或附加偏移量。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | 数据流。 |
| additional_data_offset | int | 附加数据偏移量。 |

