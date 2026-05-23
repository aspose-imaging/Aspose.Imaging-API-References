---
title: "Класс ImageCreatorsRegistry"
type: docs
weight: 5690
url: /ru/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Получает зарегистрированные дескрипторы. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Возвращает зарегистрированные форматы создания изображений. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Создаёт первый найденный создатель, подходящий для указанного. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Возвращает первый найденный поддерживаемый дескриптор, подходящий для указанного. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Регистрирует указанный дескриптор создателя изображения. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Регистрирует создателя. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Отменяет регистрацию создателя. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Создаёт первый найденный создатель, подходящий для указанного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Создатель, поддерживающий указанный, или null, если такой создатель не найден. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Возвращает первый найденный поддерживаемый дескриптор, подходящий для указанного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Дескриптор создателя, поддерживающий указанный, или null, если такой дескриптор не найден. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Регистрирует указанный дескриптор создателя изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Дескриптор создателя изображения. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Регистрирует создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Дескриптор создателя для регистрации. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Отменяет регистрацию создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Дескриптор создателя. |

