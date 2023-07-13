---
title: DataStreamSupporter Class
type: docs
weight: 1310
url: /python-net/aspose.imaging/datastreamsupporter/
---

The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.Imaging Version:** 23.6

The DataStreamSupporter type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| is_cached | bool | r | Gets a value indicating whether object's data is cached currently and no data reading is required. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| save() | Saves the object's data to the current [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save(stream)](#save_stream_0) | Saves the object's data to the specified stream. |
| [save(file_path)](#save_file_path_1) | Saves the object's data to the specified file location. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Saves the object's data to the specified file location. |
| cache_data() | Caches the data and ensures no additional data loading will be performed from the underlying [data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save_to_stream(stream)](#save_to_stream_stream_3) | Saves the object's data to the specified stream. |

### save(stream) {#save_stream_0}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |

### save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### save_to_stream(stream) {#save_to_stream_stream_3}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

