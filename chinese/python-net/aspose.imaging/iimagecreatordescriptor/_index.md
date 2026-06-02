---
title: "IImageCreatorDescriptor 类"
type: docs
weight: 5300
url: /zh/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | 确定图像创建器是否可以使用 _imageOptions_ 创建新图像。 |
| [create_instance()](#create_instance__2) | 创建一个新的创建器实例。 |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

确定图像创建器是否可以使用 _imageOptions_ 创建新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> 如果此描述符创建的图像创建器可以使用指定的 _imageOptions_ 创建图像数据；否则为 <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的创建器实例。

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | 一个新的创建器实例。 |


