---
title: "StreamExtensions Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.extensions/streamextensions/
---

**Summary:** Provides access to the creation of a MemoryStream or FileStream.

**Module:** [aspose.imaging.extensions](/imaging/python-net/aspose.imaging.extensions/)

**Full Name:** aspose.imaging.extensions.StreamExtensions

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_file_stream(path, file_mode)](#create_file_stream_path_file_mode_1) | Erstellt einen FileStream. |
| [create_memory_stream()](#create_memory_stream__2) | Erstellt einen MemoryStream. |
| [create_memory_stream_from_bytes(array)](#create_memory_stream_from_bytes_array_3) | Erstellt einen MemoryStream mit einem angegebenen Array darin. |
| [create_memory_stream_with_size(capacity)](#create_memory_stream_with_size_capacity_4) | Erstellt einen MemoryStream mit einer angegebenen Kapazität. |


### Method: create_file_stream(path, file_mode)  [static] {#create_file_stream_path_file_mode_1}


```
 create_file_stream(path, file_mode) 
```

Erstellt einen FileStream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad. |
| file_mode | FileMode | Der Dateimodus. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Die FileStream-Instanz. |


### Method: create_memory_stream()  [static] {#create_memory_stream__2}


```
 create_memory_stream() 
```

Erstellt einen MemoryStream.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Die MemoryStream-Instanz. |


### Method: create_memory_stream_from_bytes(array)  [static] {#create_memory_stream_from_bytes_array_3}


```
 create_memory_stream_from_bytes(array) 
```

Erstellt einen MemoryStream mit einem angegebenen Array darin.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| array | System.Byte | Das Array zum Einwickeln. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Die MemoryStream-Instanz. |


### Method: create_memory_stream_with_size(capacity)  [static] {#create_memory_stream_with_size_capacity_4}


```
 create_memory_stream_with_size(capacity) 
```

Erstellt einen MemoryStream mit einer angegebenen Kapazität.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| capacity | int | Die Kapazität. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Die MemoryStream-Instanz. |


