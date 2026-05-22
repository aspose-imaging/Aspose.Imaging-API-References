---
title: "StreamExtensions فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | ينشئ FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | ينشئ MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | ينشئ MemoryStream بمصفوفة محددة داخله. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | ينشئ MemoryStream بسعة محددة. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

ينشئ FileStream.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار. |
| file_mode | FileMode | وضع الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | مثيل FileStream. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

ينشئ MemoryStream.

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | مثيل MemoryStream. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

ينشئ MemoryStream بمصفوفة محددة داخله.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| array | System.Byte | المصفوفة للتغليف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | مثيل MemoryStream. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

ينشئ MemoryStream بسعة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| capacity | int | السعة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | مثيل MemoryStream. |


