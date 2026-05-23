---
title: "Класс IImageCreatorDescriptor"
type: docs
weight: 5300
url: /ru/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Определяет, может ли создатель изображения создать новое изображение, используя _imageOptions_. |
| [create_instance()](#create_instance__2) | Создает новый экземпляр создателя. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Определяет, может ли создатель изображения создать новое изображение, используя _imageOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>True</c> если создатель изображения, созданный этим дескриптором, может создать данные изображения, используя указанные _imageOptions_; иначе, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создает новый экземпляр создателя.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Новый экземпляр создателя. |


