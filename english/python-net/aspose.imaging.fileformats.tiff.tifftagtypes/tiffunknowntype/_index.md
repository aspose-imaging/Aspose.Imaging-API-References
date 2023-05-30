---
title: TiffUnknownType Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---

The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

**Namespace:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Class Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffUnknownType

**Assembly:**  Aspose.Imaging Version: 23.5.6

The TiffUnknownType type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value)|Initializes a new instance of the TiffUnknownType class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|element_size|Gets the element size in bytes.|
|data_size|Gets the tag value size.|
|count|Gets the count of elements.|
|id|Gets tag id as number.|
|tag_id|Gets the tag id.|
|tag_type|Gets the tag type.|
|value|Gets or sets the value this data type contains.|
|is_valid|Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored.|
|offset_or_value|Gets the offset value for an additional data or value itself in case count is 1.|
|stream|Gets the stream to read additional data from.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_aligned_data_size(size_of_tag_value)|Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary.|
|get_additional_data_size(size_of_tag_value)|Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value).|
|read_tag(data_stream, position)|Reads the tag data.|
|compare_to(obj)|Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.|
|deep_clone()|Performs a deep clone of this instance.|
|write_tag(data_stream, additional_data_offset)|Writes the tag value or additional offset.|
|write_additional_data(data_stream)|Writes the additional tag data.|
