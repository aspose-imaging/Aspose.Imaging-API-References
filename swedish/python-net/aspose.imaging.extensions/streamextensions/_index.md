---
title: "StreamExtensions klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Skapar en FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Skapar en MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Skapar en MemoryStream med en given array inuti. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Skapar en MemoryStream med en given kapacitet. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Skapar en FileStream.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen. |
| file_mode | FileMode | Filläget. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | FileStream-instansen. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Skapar en MemoryStream.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | MemoryStream-instansen. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Skapar en MemoryStream med en given array inuti.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| array | System.Byte | Arrayen för omslag. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | MemoryStream-instansen. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Skapar en MemoryStream med en given kapacitet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| capacity | int | Kapaciteten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | MemoryStream-instansen. |


