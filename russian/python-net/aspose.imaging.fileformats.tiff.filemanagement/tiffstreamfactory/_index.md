---
title: "Класс TiffStreamFactory"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---

**Summary:** The Tiff stream factory based on byte endianness.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffStreamFactory

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)](#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1) | Получает считыватель tiff‑потока. |
| [get_tiff_reader(stream, byte_order, is_big_tiff)](#get_tiff_reader_stream_byte_order_is_big_tiff_2) | Получает считыватель tiff‑потока. |
| [get_tiff_writer(stream, byte_order, is_big_tiff)](#get_tiff_writer_stream_byte_order_is_big_tiff_3) | Получает записыватель tiff‑потока. |


### Method: get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff)  [static] {#get_tiff_reader_bytes_bytes_offset_data_length_byte_order_is_big_tiff_1}


```
 get_tiff_reader(bytes, bytes_offset, data_length, byte_order, is_big_tiff) 
```

Получает считыватель tiff‑потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | System.Byte | Байты. |
| bytes_offset | int | Смещение байтов. |
| data_length | int | Длина данных. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Порядок байтов. |
| is_big_tiff | bool | Указывает тип Tiff: оригинальный или большой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Поток Tiff, подходящий для чтения. |


### Method: get_tiff_reader(stream, byte_order, is_big_tiff)  [static] {#get_tiff_reader_stream_byte_order_is_big_tiff_2}


```
 get_tiff_reader(stream, byte_order, is_big_tiff) 
```

Получает считыватель tiff‑потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Порядок байтов. |
| is_big_tiff | bool | Указывает тип TIFF. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Поток Tiff, подходящий для чтения. |


### Method: get_tiff_writer(stream, byte_order, is_big_tiff)  [static] {#get_tiff_writer_stream_byte_order_is_big_tiff_3}


```
 get_tiff_writer(stream, byte_order, is_big_tiff) 
```

Получает записыватель tiff‑потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Порядок байтов. |
| is_big_tiff | bool | Указывает тип TIFF. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Поток Tiff, подходящий для записи. |


