---
title: IImageCreatorDescriptor Class
type: docs
weight: 5260
url: /python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determines whether image creator can create a new image using the _imageOptions_. |
| [create_instance()](#create_instance__2) | Creates a new creator instance. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determines whether image creator can create a new image using the _imageOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> if image creator created by this descriptor can create image data using the specified _imageOptions_; otherwise, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Creates a new creator instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | A new creator instance. |


