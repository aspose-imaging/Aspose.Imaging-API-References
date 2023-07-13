---
title: TiffRationalType Class
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---

The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffRationalType

**Inheritance:** TiffCommonArrayType

**Aspose.Imaging Version:** 23.6

The TiffRationalType type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [TiffRationalType(tag_id)](#TiffRationalType_tag_id_0) | Initializes a new instance of the TiffRationalType class |
| [TiffRationalType(tag_id)](#TiffRationalType_tag_id_1) | Initializes a new instance of the TiffRationalType class |
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
| values_container | Array | r | Gets the values container. |
| values | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | r/w | Gets or sets the values. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_2) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_4) | Reads the tag data. |
| [compare_to(obj)](#compare_to_obj_5) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [deep_clone()](#deep_clone__6) | Performs a deep clone of this instance. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | Writes the tag value or additional offset. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Writes the additional tag data. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_9) | Initializes a new instance of the [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) class. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_10) | Initializes a new instance of the [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) class. |

### TiffRationalType(tag_id) {#TiffRationalType_tag_id_0}


```
 TiffRationalType(tag_id) 
```

Initializes a new instance of the TiffRationalType class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) |  |

### TiffRationalType(tag_id) {#TiffRationalType_tag_id_1}


```
 TiffRationalType(tag_id) 
```

Initializes a new instance of the TiffRationalType class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | ushort |  |

### get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_2}


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


### get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


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


### read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_4}


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


### compare_to(obj) {#compare_to_obj_5}


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


### deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Performs a deep clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype) | A deep clone of the current instance. |


### write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

Writes the tag value or additional offset.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | The data stream. |
| additional_data_offset | long | The additional data offset. |

### write_additional_data(data_stream) {#write_additional_data_data_stream_8}


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


### create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_9}


```
 create_with_tag(tag_id) 
```

Initializes a new instance of the [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag id. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype) |  |


### create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_10}


```
 create_with_tag_id(tag_id) 
```

Initializes a new instance of the [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | ushort | The tag id. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype) |  |


