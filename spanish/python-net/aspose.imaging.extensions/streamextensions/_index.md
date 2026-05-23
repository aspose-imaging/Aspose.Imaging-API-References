---
title: "StreamExtensions Clase"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Crea un FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Crea un MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Crea un MemoryStream con una matriz dada dentro. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Crea un MemoryStream con una capacidad dada. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Crea un FileStream.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta. |
| file_mode | FileMode | El modo de archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | La instancia de FileStream. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Crea un MemoryStream.

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | La instancia de MemoryStream. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Crea un MemoryStream con una matriz dada dentro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matriz | System.Byte | La matriz para envolver. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | La instancia de MemoryStream. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Crea un MemoryStream con una capacidad dada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| capacity | int | La capacidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | La instancia de MemoryStream. |


