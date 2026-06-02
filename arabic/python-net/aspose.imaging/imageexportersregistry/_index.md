---
title: "الفئة ImageExportersRegistry"
type: docs
weight: 5700
url: /ar/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | يحصل على أوصاف المصدر المسجل. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | يحصل على صيغ التصدير المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | ينشئ أول مصدر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | يسجل وصف مصدر الصورة المحدد. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | يسجل المصدر. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | يلغي تسجيل المصدر. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

ينشئ أول مصدر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد تصديرها. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الحفظ المستخدمة للتصدير. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | المصدر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يتم العثور على مصدر كهذا. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد تصديرها. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | الخيارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | وصف المصدر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يتم العثور على وصف كهذا. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

يسجل وصف مصدر الصورة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | وصف مصدر الصورة. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

يسجل المصدر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | وصف المصدر للتسجيل. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

يلغي تسجيل المصدر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | وصف المصدر لإلغاء التسجيل. |

