---
title: "Clase TiffStreamFactory"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | Obtiene el lector de flujo tiff. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | Obtiene el lector de flujo tiff. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | Obtiene el escritor de flujo tiff. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

Obtiene el lector de flujo tiff.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | System.Byte | Los bytes. |
| bytes_offset | int | El desplazamiento de bytes. |
| data_length | int | Longitud de los datos. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | El orden de bytes. |
| is_big_tiff | bool | Indica el tipo Tiff: original o grande. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flujo Tiff adecuado para lectura. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

Obtiene el lector de flujo tiff.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor del flujo. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | El orden de bytes. |
| is_big_tiff | bool | Indica el tipo TIFF. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Flujo Tiff adecuado para lectura. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

Obtiene el escritor de flujo tiff.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor del flujo. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | El orden de bytes. |
| is_big_tiff | bool | Indica el tipo TIFF. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Flujo Tiff adecuado para escritura. |


