---
title: BigTiffReader Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

The little endian BigTiff reader.

**Namespace:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Class Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Assembly:**  Aspose.Imaging Version: 23.5.6

The BigTiffReader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|BigTiffReader(data)|Initializes a new instance of the BigTiffReader class|
|BigTiffReader(stream_container)|Initializes a new instance of the BigTiffReader class|
|BigTiffReader(data, start_index)|Initializes a new instance of the BigTiffReader class|
|BigTiffReader(data, start_index, data_length)|Initializes a new instance of the BigTiffReader class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|length|Gets the reader length.|
|throw_exceptions|Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|read_bytes(array, array_index, position, count)|  |
|read_bytes(position, count)|  |
|read_double(position)|  |
|read_double_array(position, count)|Reads an array of double values from the stream.|
|read_float(position)|  |
|read_float_array(position, count)|Reads an array of float values from the stream.|
|read_rational(position)|  |
|read_s_rational(position)|  |
|read_rational_array(position, count)|Reads an array of rational values from the stream.|
|read_s_rational_array(position, count)|Reads an array of signed rational values from the stream.|
|read_s_byte(position)|  |
|read_s_byte_array(position, count)|Reads an array of signed byte values from the stream.|
|read_s_int(position)|  |
|read_s_int_array(position, count)|Reads an array of signed integer values from the stream.|
|read_s_short(position)|  |
|read_s_short_array(position, count)|Reads an array of signed short values from the stream.|
|read_u_int(position)|  |
|read_u_int_array(position, count)|Reads an array of unsigned integer values from the stream.|
|read_u_short(position)|  |
|read_u_short_array(position, count)|Reads an array of unsigned integer values from the stream.|
|read_long(position)|Read unsigned long value from the stream.|
|read_long_array(position, count)|Reads an array of ulong values from the stream.|
|read_u_long(position)|Read unsigned long value from the stream.|
|read_u_long_array(position, count)|Reads an array of ulong values from the stream.|
|to_stream_container(start_position)|Converts the underlying data to the stream container.|
