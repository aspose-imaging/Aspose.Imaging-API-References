---
title: "Classe IImageCreatorDescriptor"
type: docs
weight: 5300
url: /it/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determina se il creatore di immagini può creare una nuova immagine usando le _imageOptions_. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza del creatore. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determina se il creatore di immagini può creare una nuova immagine usando le _imageOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>True</c> se il creatore di immagini creato da questo descrittore può generare dati immagine usando le _imageOptions_ specificate; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza del creatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Una nuova istanza del creatore. |


