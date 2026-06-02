---
title: "Classe TiffStreamFactory"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | Obtient le lecteur de flux tiff. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | Obtient le lecteur de flux tiff. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | Obtient l'écrivain de flux tiff. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

Obtient le lecteur de flux tiff.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | System.Byte | Les octets. |
| bytes_offset | int | Le décalage des octets. |
| data_length | int | Longueur des données. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordre des octets. |
| is_big_tiff | bool | Indique le type Tiff : original ou grand. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flux Tiff adapté à la lecture. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

Obtient le lecteur de flux tiff.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordre des octets. |
| is_big_tiff | bool | Indique le type TIFF. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flux Tiff adapté à la lecture. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

Obtient l'écrivain de flux tiff.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordre des octets. |
| is_big_tiff | bool | Indique le type TIFF. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Flux Tiff adapté à l'écriture. |


