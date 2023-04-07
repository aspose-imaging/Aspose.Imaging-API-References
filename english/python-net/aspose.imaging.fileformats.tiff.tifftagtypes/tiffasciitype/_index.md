---
title: TiffASCIIType Class
type: docs
weight: 10
url: /python-net/api-reference/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---

The tiff ascii type.

**Namespace:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/api-reference/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Class Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffASCIIType

**Assembly:**  Aspose.Imaging Version: 23.3.0

The TiffASCIIType type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TiffASCIIType(tag_id)|Initializes a new instance of the TiffASCIIType class|
|TiffASCIIType(tag_id)|Initializes a new instance of the TiffASCIIType class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|count|Gets the count of elements.|
|id|Gets tag id integer representation.|
|tag_id|Gets the tag id.|
|tag_type|Gets the tag type.|
|aligned_data_size|Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).|
|data_size|Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).|
|value|Gets or sets the value this data type contains.|
|is_valid|Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored.|
|text|Gets or sets the text.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|read_tag(data_stream, position)|Reads the tag data.|
|compare_to(obj)|Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.|
|deep_clone()|Performs a deep clone of this instance.|
|write_tag(data_stream, additional_data_offset)|Writes the tag value or additional offset.|
|write_additional_data(data_stream)|Writes the additional tag data.|
|create_with_tag(tag_id)|Initializes a new instance of the [TiffASCIIType](/imaging/python-net/api-reference/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/) class.|
|create_with_tag_id(tag_id)|Initializes a new instance of the [TiffASCIIType](/imaging/python-net/api-reference/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/) class.|
