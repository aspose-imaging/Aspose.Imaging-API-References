---
title: "StreamExtensions Classe"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Crea un FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Crea un MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Crea un MemoryStream con un array fornito al suo interno. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Crea un MemoryStream con una capacità specificata. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Crea un FileStream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| percorso | string | Il percorso. |
| file_mode | FileMode | La modalità di file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | L'istanza di FileStream. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Crea un MemoryStream.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | L'istanza di MemoryStream. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Crea un MemoryStream con un array fornito al suo interno.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | System.Byte | L'array per l'incapsulamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | L'istanza di MemoryStream. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Crea un MemoryStream con una capacità specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| capacity | int | La capacità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | L'istanza di MemoryStream. |


