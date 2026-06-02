---
title: "DataStreamSupporter 类"
type: docs
weight: 1360
url: /zh/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| is_cached | bool | r | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) 进行额外的数据加载。 |
| save() | 将对象的数据保存到当前的 [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/)。 |
| [save(file_path)](#save_file_path_1) | 将对象的数据保存到指定的文件位置。 |
| [save(file_path, over_write)](#save_file_path_over_write_2) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_3) | 将对象的数据保存到指定的流中。 |
| [save_to_stream(stream)](#save_to_stream_stream_4) | 将对象的数据保存到指定的流中。 |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

