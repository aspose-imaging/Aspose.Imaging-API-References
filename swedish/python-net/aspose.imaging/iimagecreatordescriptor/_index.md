---
title: "IImageCreatorDescriptor-klass"
type: docs
weight: 5300
url: /sv/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Bestämmer om bildskaparen kan skapa en ny bild med hjälp av _imageOptions_. |
| [create_instance()](#create_instance__2) | Skapar en ny skapareinstans. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Bestämmer om bildskaparen kan skapa en ny bild med hjälp av _imageOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bildalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>True</c> om bildskaparen som skapats av denna beskrivare kan skapa bilddata med de angivna _imageOptions_; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny skapareinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | En ny skapareinstans. |


