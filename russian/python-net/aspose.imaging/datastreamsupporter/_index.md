---
title: "Класс DataStreamSupporter"
type: docs
weight: 1360
url: /ru/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| is_cached | bool | r | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Кеширует данные и гарантирует, что из базового [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) не будет выполнена дополнительная загрузка данных. |
| save() | Сохраняет данные объекта в текущий [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Сохраняет данные объекта в указанное расположение файла. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_3) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | Сохраняет данные объекта в указанный поток. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

