---
title: "StreamExtensions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | 创建一个 FileStream。 |
| [create_memory_stream()](#create_memory_stream__2) | 创建一个 MemoryStream。 |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | 使用给定数组创建一个 MemoryStream。 |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | 创建一个具有给定容量的 MemoryStream。 |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

创建一个 FileStream。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | 路径。 |
| file_mode | FileMode | 文件模式。 |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | FileStream 实例。 |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

创建一个 MemoryStream。

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | MemoryStream 实例。 |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

使用给定数组创建一个 MemoryStream。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| array | System.Byte | 用于包装的数组。 |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | MemoryStream 实例。 |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

创建一个具有给定容量的 MemoryStream。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| capacity | int | 容量。 |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | MemoryStream 实例。 |


