---
title: TiffShortType Class
type: docs
weight: 160
url: /python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/
---

**Summary:** The tiff short type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffShortType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffShortType(tag_id)](#TiffShortType_tag_id_1) | Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class. |
| [TiffShortType(tag_id)](#TiffShortType_tag_id_2) | Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Gets the count of elements. |
| data_size | int | r | Gets the tag value size. |
| element_size | System.Byte | r | Gets the element size in bytes. |
| id | int | r | Gets tag id as number. |
| is_valid | bool | r | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Gets the tag id. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Gets the tag type. |
| value | System.Object | r/w | Gets or sets the value this data type contains. |
| values | int[] | r/w | Gets or sets the data. |
| values_container | System.Array | r | Gets the values container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class. |
| [deep_clone()](#deep_clone__4) | Performs a deep clone of this instance. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Reads the tag data. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Writes the additional tag data. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Writes the tag value or additional offset. |


### Constructor: TiffShortType(tag_id) {#TiffShortType_tag_id_1}


```
 TiffShortType(tag_id) 
```

Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag id. |

### Constructor: TiffShortType(tag_id) {#TiffShortType_tag_id_2}


```
 TiffShortType(tag_id) 
```

Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | int | The tag id. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| obj | System.Object | An object to compare with this instance. |

**Returns**

| Type | Description |
| :- | :- |
| int | A 32-bit signed integer that indicates the relative order of the objects being compared. The return value has these meanings:<br/>            Value<br/>            Meaning<br/>            Less than zero<br/>            This instance is less than _obj_.<br/>            Zero<br/>            This instance is equal to _obj_.<br/>            Greater than zero<br/>            This instance is greater than _obj_. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag id. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Initializes a new instance of the [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_id | int | The tag id. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffShortType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Performs a deep clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | A deep clone of the current instance. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Size of tag value: 4 or 8 for BigTiff. |

**Returns**

| Type | Description |
| :- | :- |
| int | The additional data size in bytes. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Size of tag value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The aligned data size in bytes. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Reads the tag data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | The data stream. |
| position | int | The tag position. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The read tag. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


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
| int | The actual bytes written. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Writes the tag value or additional offset.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | The data stream. |
| additional_data_offset | int | The additional data offset. |

