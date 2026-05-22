---
title: "الفئة IImageExporterDescriptor"
type: docs
weight: 5330
url: /ar/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | يحدد ما إذا كان مُصدّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ. |
| [create_instance()](#create_instance__2) | ينشئ نسخة جديدة من المُصدّر. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

يحدد ما إذا كان مُصدّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد تصديرها. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | قاعدة الخيارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>True</c> إذا كان المُصدّر الذي أنشأه هذا الوصف يمكنه تصدير الصورة المحددة إلى تنسيق الملف المحدد؛ وإلا، <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ نسخة جديدة من المُصدّر.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | نسخة جديدة من المُصدّر. |


