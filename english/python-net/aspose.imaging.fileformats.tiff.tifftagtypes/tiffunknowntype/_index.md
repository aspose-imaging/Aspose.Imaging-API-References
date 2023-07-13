---
title: TiffUnknownType Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---

The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffUnknownType

**Inheritance:** TiffDataType

**Aspose.Imaging Version:** 23.6

The TiffUnknownType type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value)](#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_0) | Initializes a new instance of the [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| element_size | byte | r | Gets the element size in bytes. |
| data_size | ulong | r | Gets the tag value size. |
| count | ulong | r | Gets the count of elements. |
| id | ushort | r | Gets tag id as number. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Gets the tag id. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Gets the tag type. |
| value | object | r/w | Gets or sets the value this data type contains. |
| is_valid | bool | r | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| offset_or_value | ulong | r | Gets the offset value for an additional data or value itself in case count is 1. |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | r | Gets the stream to read additional data from. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_1) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_2) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Reads the tag data. |
| [compare_to(obj)](#compare_to_obj_4) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [deep_clone()](#deep_clone__5) | Performs a deep clone of this instance. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_6) | Writes the tag value or additional offset. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_7) | Writes the additional tag data. |

### TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) {#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_0}


```
 TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) 
```

Initializes a new instance of the [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | The stream to read from. |
| tag_type | ushort | Type of the tag. |
| tag_id | ushort | The tag id. |
| count | ulong | The count value. |
| offset_or_value | ulong | The offset or value. |

### get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_1}


```
 get_aligned_data_size(size_of_tag_value) 
```

Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size_of_tag_value | byte | Size of tag value. |

**Returns**

| Type | Description |
| :- | :- |
| ulong | The aligned data size in bytes. |


### get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_2}


```
 get_additional_data_size(size_of_tag_value) 
```

Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size_of_tag_value | byte | Size of tag value: 4 or 8 for BigTiff. |

**Returns**

| Type | Description |
| :- | :- |
| ulong | The additional data size in bytes. |


### read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Reads the tag data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | The data stream. |
| position | long | The tag position. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype) | The read tag. |


### compare_to(obj) {#compare_to_obj_4}


```
 compare_to(obj) 
```

Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| obj | object | An object to compare with this instance. |

**Returns**

| Type | Description |
| :- | :- |
| int | A 32-bit signed integer that indicates the relative order of the objects being compared. The return value has these meanings:<br/>            Value<br/>            Meaning<br/>            Less than zero<br/>            This instance is less than <paramref name="obj" />.<br/>            Zero<br/>            This instance is equal to <paramref name="obj" />.<br/>            Greater than zero<br/>            This instance is greater than <paramref name="obj" />. |


### deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Performs a deep clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype) | A deep clone of the current instance. |


### write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_6}


```
 write_tag(data_stream, additional_data_offset) 
```

Writes the tag value or additional offset.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | The data stream. |
| additional_data_offset | long | The additional data offset. |

### write_additional_data(data_stream) {#write_additional_data_data_stream_7}


```
 write_additional_data(data_stream) 
```

Writes the additional tag data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | The data stream. |

**Returns**

| Type | Description |
| :- | :- |
| long | The actual bytes written. |


