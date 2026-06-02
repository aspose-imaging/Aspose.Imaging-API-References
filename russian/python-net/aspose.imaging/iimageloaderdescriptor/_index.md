---
title: "Класс IImageLoaderDescriptor"
type: docs
weight: 5350
url: /ru/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и, при необходимости, используя _loadOptions_. |
| [create_instance()](#create_instance__2) | Создаёт новый экземпляр загрузчика. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и, при необходимости, используя _loadOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Подробности формата файла, указанные в _loadOptions_. _loadOptions_ может быть null. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если загрузчик изображений, созданный этим дескриптором, может читать изображение из потока; иначе <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создаёт новый экземпляр загрузчика.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Новый экземпляр загрузчика. |


