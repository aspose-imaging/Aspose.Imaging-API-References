---
title: StreamExtensions Class
type: docs
weight: 170
url: /python-net/aspose.imaging.extensions/streamextensions/
---

Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

**Aspose.Imaging Version:** 23.6

The StreamExtensions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [StreamExtensions()](#StreamExtensions__0) | Initializes a new instance of the StreamExtensions class |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_memory_stream()](#create_memory_stream__1) | Creates a MemoryStream. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_2) | Creates a MemoryStream with a given capacity. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Creates a MemoryStream with a given array inside. |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_4) | Creates a FileStream. |

### StreamExtensions() {#StreamExtensions__0}


```
 StreamExtensions() 
```

Initializes a new instance of the StreamExtensions class

### create_memory_stream()  [static] {#create_memory_stream__1}


```
 create_memory_stream() 
```

Creates a MemoryStream.

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The MemoryStream instance. |


### create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_2}


```
 create_memory_stream_with_size(capacity) 
```

Creates a MemoryStream with a given capacity.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| capacity | int | The capacity. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The MemoryStream instance. |


### create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Creates a MemoryStream with a given array inside.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| array | byte | The array for wrapping. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The MemoryStream instance. |


### create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_4}


```
 create_file_stream(path, file_mode) 
```

Creates a FileStream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path. |
| file_mode | System.IO.FileMode | The file mode. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The FileStream instance. |


