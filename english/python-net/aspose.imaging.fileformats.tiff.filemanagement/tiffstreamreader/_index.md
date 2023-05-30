---
title: TiffStreamReader Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---

The tiff stream for handling little endian tiff file format.

**Namespace:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Class Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader

**Assembly:**  Aspose.Imaging Version: 23.5.6

The TiffStreamReader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TiffStreamReader(data)|Initializes a new instance of the TiffStreamReader class|
|TiffStreamReader(data, start_index)|Initializes a new instance of the TiffStreamReader class|
|TiffStreamReader(data, start_index, data_length)|Initializes a new instance of the TiffStreamReader class|
|TiffStreamReader(stream_container)|Initializes a new instance of the TiffStreamReader class|
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
