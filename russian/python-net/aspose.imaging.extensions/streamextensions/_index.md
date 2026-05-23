---
title: "Класс StreamExtensions"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Создаёт FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Создаёт MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Создаёт MemoryStream с заданным массивом внутри. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Создает MemoryStream с заданной емкостью. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Создаёт FileStream.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| путь | string | Путь. |
| file_mode | FileMode | Режим файла. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Экземпляр FileStream. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Создаёт MemoryStream.

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Экземпляр MemoryStream. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Создаёт MemoryStream с заданным массивом внутри.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| array | System.Byte | Массив для обёртки. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Экземпляр MemoryStream. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Создает MemoryStream с заданной емкостью.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| capacity | int | Емкость. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Экземпляр MemoryStream. |


