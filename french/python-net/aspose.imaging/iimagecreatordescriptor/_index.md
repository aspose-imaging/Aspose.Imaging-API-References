---
title: "Classe IImageCreatorDescriptor"
type: docs
weight: 5300
url: /fr/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Détermine si le créateur d'image peut créer une nouvelle image en utilisant les _imageOptions_. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance du créateur. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Détermine si le créateur d'image peut créer une nouvelle image en utilisant les _imageOptions_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> si le créateur d'image créé par ce descripteur peut créer des données d'image en utilisant les _imageOptions_ spécifiés ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance du créateur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Une nouvelle instance du créateur. |


