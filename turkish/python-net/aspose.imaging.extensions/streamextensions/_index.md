---
title: "StreamExtensions Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Bir FileStream oluşturur. |
| [create_memory_stream()](#create_memory_stream__2) | Bir MemoryStream oluşturur. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | İçinde verilen bir diziyle bir MemoryStream oluşturur. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Verilen bir kapasiteyle bir MemoryStream oluşturur. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Bir FileStream oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Yol. |
| file_mode | FileMode | Dosya modu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | FileStream örneği. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Bir MemoryStream oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | MemoryStream örneği. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

İçinde verilen bir diziyle bir MemoryStream oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| array | System.Byte | Sarma için dizi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | MemoryStream örneği. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Verilen bir kapasiteyle bir MemoryStream oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| capacity | int | Kapasite. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | MemoryStream örneği. |


