---
title: "TiffUnknownType 类"
type: docs
weight: 180
url: /zh/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---

**Summary:** The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffUnknownType

**Inheritance:** TiffDataType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value)](#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1) | 初始化 [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取元素的计数。 |
| data_size | int | r | 获取标签值的大小。 |
| element_size | System.Byte | r | 获取元素的字节大小。 |
| id | int | r | 获取标签 ID（数字）。 |
| is_valid | bool | r | 获取一个值，指示标签数据是否有效。有效的标签包含可保留的数据。无效的标签无法存储。 |
| offset_or_value | int | r | 获取附加数据的偏移值，或在计数为 1 时获取值本身。 |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | r | 获取用于读取附加数据的流。 |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | 获取标签 ID。 |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | 获取标签类型。 |
| value | System.Object | r/w | 获取或设置此数据类型包含的值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于、跟随还是与另一个对象处于相同位置。 |
| [deep_clone()](#deep_clone__2) | 对该实例执行深度克隆。 |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | 获取附加标签值的大小（以字节为单位）（如果标签无法容纳完整的标签值）。 |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_4) | 获取按4字节（int）或8字节（long）边界对齐的数据大小。 |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_5) | 读取标签数据。 |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_6) | 写入附加标签数据。 |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | 写入标签值或附加偏移量。 |


### Constructor: TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) {#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1}


```
 TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) 
```

初始化 [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | 用于读取的流。 |
| tag_type | int | 标签的类型。 |
| tag_id | int | 标签 ID。 |
| count | int | 计数值。 |
| offset_or_value | int | 偏移或值。 |

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


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

对该实例执行深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 当前实例的深度克隆。 |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


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


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_4}


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


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_5}


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


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_6}


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


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

写入标签值或附加偏移量。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | 数据流。 |
| additional_data_offset | int | 附加数据偏移量。 |

