---
title: "Класс ImageExportersRegistry"
type: docs
weight: 5700
url: /ru/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | Получает зарегистрированные дескрипторы экспортёров. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получает зарегистрированные форматы экспорта. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Регистрирует указанный дескриптор экспортёра изображений. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Регистрирует экспортер. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Отменяет регистрацию экспортера. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для экспорта. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры сохранения, используемые для экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | Экспортер, поддерживающий указанное изображение и параметры сохранения, или null, если такой экспортер не найден. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для экспорта. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Дескриптор экспортера, поддерживающий указанное изображение и параметры сохранения, или null, если такой дескриптор не найден. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Регистрирует указанный дескриптор экспортёра изображений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Дескриптор экспортера изображений. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Регистрирует экспортер.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Дескриптор экспортера для регистрации. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Отменяет регистрацию экспортера.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Дескриптор экспортера для отмены регистрации. |

