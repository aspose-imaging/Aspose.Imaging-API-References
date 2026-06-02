---
title: "IImageCreatorDescriptor فئة"
type: docs
weight: 5300
url: /ar/python-net/aspose.imaging/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageCreatorDescriptor

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام _imageOptions_. |
| [create_instance()](#create_instance__2) | ينشئ مثيلًا جديدًا للمنشئ. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام _imageOptions_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>True</c> إذا كان منشئ الصورة الذي أنشأه هذا الوصف يمكنه إنشاء بيانات الصورة باستخدام _imageOptions_ المحدد؛ وإلا، <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ مثيلًا جديدًا للمنشئ.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | مثيل جديد للمنشئ. |


