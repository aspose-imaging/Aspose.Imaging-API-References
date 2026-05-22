---
title: "فئة TiffStreamFactory"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | يحصل على قارئ تدفق tiff. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | يحصل على قارئ تدفق tiff. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | يحصل على كاتب تدفق tiff. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

يحصل على قارئ تدفق tiff.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| بايتات | System.Byte | البايتات. |
| bytes_offset | int | إزاحة البايتات. |
| data_length | int | طول البيانات. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت. |
| is_big_tiff | bool | يشير إلى نوع Tiff: أصلي أو كبير. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | تدفق Tiff مناسب للقراءة. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

يحصل على قارئ تدفق tiff.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت. |
| is_big_tiff | bool | يشير إلى نوع TIFF. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | تدفق Tiff مناسب للقراءة. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

يحصل على كاتب تدفق tiff.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | ترتيب البايت. |
| is_big_tiff | bool | يشير إلى نوع TIFF. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | تدفق Tiff مناسب للكتابة. |


