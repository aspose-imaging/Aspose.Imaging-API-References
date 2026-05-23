---
title: "Класс IImageExporterDescriptor"
type: docs
weight: 5330
url: /ru/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Определяет, может ли экспортёр изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения. |
| [create_instance()](#create_instance__2) | Создаёт новый экземпляр экспортёра. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Определяет, может ли экспортёр изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для экспорта. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | База параметров. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>True</c> если экспортёр, созданный этим дескриптором, может экспортировать указанное изображение в указанный файловый формат; иначе <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создаёт новый экземпляр экспортёра.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Новый экземпляр экспортёра. |


