---
title: "Класс ImageLoadersRegistry"
type: docs
weight: 5720
url: /ru/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Получает зарегистрированные дескрипторы. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получает зарегистрированные форматы загрузки изображений. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Создаёт первый найденный загрузчик, подходящий для указанного _stream_ и, при необходимости, _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного _stream_ и, при необходимости, _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Получает первый поддерживаемый формат файла по его имени типа. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Регистрирует указанный дескриптор загрузчика изображений. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Регистрирует загрузчик. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Отменяет регистрацию загрузчика. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Создаёт первый найденный загрузчик, подходящий для указанного _stream_ и, при необходимости, _loadOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Загрузчик, поддерживающий указанный _stream_ и _loadOptions_, или null, если такой загрузчик не найден. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Получает первый найденный поддерживаемый дескриптор, подходящий для указанного _stream_ и, при необходимости, _loadOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Дескриптор загрузчика, поддерживающий указанный _stream_ и _loadOptions_, или null, если такой дескриптор не найден. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Получает первый поддерживаемый формат файла по его имени типа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Поддерживаемый формат файла дескриптора. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Первый найденный дескриптор загрузчика или null, если такой дескриптор не найден. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| descriptor_type_name | string | Имя типа дескриптора. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Первый найденный дескриптор загрузчика или null, если такой дескриптор не найден. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Регистрирует указанный дескриптор загрузчика изображений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Дескриптор загрузчика изображений. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Регистрирует загрузчик.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Дескриптор загрузчика для регистрации. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Отменяет регистрацию загрузчика.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Дескриптор загрузчика для отмены регистрации. |

