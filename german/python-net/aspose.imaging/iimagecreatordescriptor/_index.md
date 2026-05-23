---
title: "IImageCreatorDescriptor Klasse"
type: docs
weight: 5300
url: /de/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Bestimmt, ob der Bild-Ersteller ein neues Bild mit den _imageOptions_ erstellen kann. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Ersteller-Instanz. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Bestimmt, ob der Bild-Ersteller ein neues Bild mit den _imageOptions_ erstellen kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>True</c> wenn der vom Descriptor erstellte Bild-Ersteller Bilddaten mit den angegebenen _imageOptions_ erzeugen kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Ersteller-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Eine neue Ersteller-Instanz. |


