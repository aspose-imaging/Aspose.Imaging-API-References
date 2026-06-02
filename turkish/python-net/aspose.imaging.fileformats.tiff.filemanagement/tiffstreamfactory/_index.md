---
title: "TiffStreamFactory Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | tiff akış okuyucusunu alır. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | tiff akış okuyucusunu alır. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | tiff akış yazıcısını alır. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

tiff akış okuyucusunu alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| baytlar | System.Byte | Baytlar. |
| bytes_offset | int | Bayt ofseti. |
| data_length | int | Verinin uzunluğu. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Bayt sırası. |
| is_big_tiff | bool | Tiff türünü gösterir: orijinal veya büyük. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Okuma için uygun Tiff akışı. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

tiff akış okuyucusunu alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Akış kapsayıcısı. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Bayt sırası. |
| is_big_tiff | bool | TIFF türünü gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Okuma için uygun Tiff akışı. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

tiff akış yazıcısını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Akış kapsayıcısı. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Bayt sırası. |
| is_big_tiff | bool | TIFF türünü gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Yazma için uygun Tiff akışı. |


