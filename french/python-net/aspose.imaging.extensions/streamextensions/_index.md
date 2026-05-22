---
title: "Classe StreamExtensions"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Crée un FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Crée un MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Crée un MemoryStream avec un tableau donné à l'intérieur. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Crée un MemoryStream avec une capacité donnée. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Crée un FileStream.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| chemin | string | Le chemin. |
| file_mode | FileMode | Le mode de fichier. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | L'instance FileStream. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Crée un MemoryStream.

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | L'instance MemoryStream. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Crée un MemoryStream avec un tableau donné à l'intérieur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| array | System.Byte | Le tableau pour l'encapsulation. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | L'instance MemoryStream. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Crée un MemoryStream avec une capacité donnée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| capacity | int | La capacité. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | L'instance MemoryStream. |


