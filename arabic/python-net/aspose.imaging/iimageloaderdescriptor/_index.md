---
title: "فئة IImageLoaderDescriptor"
type: docs
weight: 5350
url: /ar/python-net/aspose.imaging/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageLoaderDescriptor

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام _loadOptions_ اختياريًا. |
| [create_instance()](#create_instance__2) | ينشئ مثيلًا جديدًا للتحميل. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام _loadOptions_ اختياريًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | تفاصيل تنسيق الملف المحددة بواسطة _loadOptions_. قد يكون _loadOptions_ فارغًا. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان محمل الصورة الذي أنشأه هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا، <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ مثيلًا جديدًا للتحميل.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | مثيل تحميل جديد. |


