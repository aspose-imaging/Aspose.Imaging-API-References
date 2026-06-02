---
title: "Classe TiffStreamFactory"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | Ottiene il lettore del flusso tiff. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | Ottiene il lettore del flusso tiff. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | Ottiene lo scrittore del flusso tiff. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

Ottiene il lettore del flusso tiff.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | System.Byte | I byte. |
| bytes_offset | int | L'offset dei byte. |
| data_length | int | Lunghezza dei dati. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordine dei byte. |
| is_big_tiff | bool | Indica il tipo Tiff: originale o grande. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flusso Tiff adatto alla lettura. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

Ottiene il lettore del flusso tiff.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordine dei byte. |
| is_big_tiff | bool | Indica il tipo TIFF. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flusso Tiff adatto alla lettura. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

Ottiene lo scrittore del flusso tiff.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordine dei byte. |
| is_big_tiff | bool | Indica il tipo TIFF. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Flusso Tiff adatto alla scrittura. |


