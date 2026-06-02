---
title: "Clase IImageCreatorDescriptor"
type: docs
weight: 5300
url: /es/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determina si el creador de imágenes puede crear una nueva imagen usando _imageOptions_. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del creador. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determina si el creador de imágenes puede crear una nueva imagen usando _imageOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>True</c> si el creador de imágenes creado por este descriptor puede crear datos de imagen usando los _imageOptions_ especificados; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del creador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Una nueva instancia del creador. |


