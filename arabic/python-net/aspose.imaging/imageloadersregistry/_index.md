---
title: "فئة ImageLoadersRegistry"
type: docs
weight: 5720
url: /ar/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | يحصل على الوصّفات المسجّلة. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | يحصل على صيغ تحميل الصور المسجَّلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | ينشئ أول محمل تم العثور عليه مناسب للمُدخَل المحدد _stream_ وبشكل اختياري _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | يحصل على الوصف المدعوم الأول الذي تم العثور عليه المناسب للمُدخَل المحدد _stream_ وبشكل اختياري _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | يحصل على أول صيغة ملف مدعومة بحسب اسم النوع الخاص بها. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | يحصل على أول وصّف مدعوم بحسب اسم النوع الخاص به. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | يسجل وصّف محمل الصورة المحدد. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | يسجل المحمل. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | يلغي تسجيل المحمل. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

ينشئ أول محمل تم العثور عليه مناسب للمُدخَل المحدد _stream_ وبشكل اختياري _loadOptions_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | المحمل الذي يدعم _stream_ و _loadOptions_ المحددين أو null إذا لم يتم العثور على محمل مماثل. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

يحصل على الوصف المدعوم الأول الذي تم العثور عليه المناسب للمُدخَل المحدد _stream_ وبشكل اختياري _loadOptions_.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | خيارات التحميل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف المحمل الذي يدعم _stream_ و _loadOptions_ المحددين أو null إذا لم يتم العثور على وصّف مماثل. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

يحصل على أول صيغة ملف مدعومة بحسب اسم النوع الخاص بها.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | صيغة ملف الوصّف المدعومة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف المحمل الأول الذي تم العثور عليه أو null إذا لم يتم العثور على وصّف مماثل. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

يحصل على أول وصّف مدعوم بحسب اسم النوع الخاص به.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| descriptor_type_name | string | اسم نوع الوصّف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف المحمل الأول الذي تم العثور عليه أو null إذا لم يتم العثور على وصّف مماثل. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

يسجل وصّف محمل الصورة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف محمل الصورة. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

يسجل المحمل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف المحمل للتسجيل. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

يلغي تسجيل المحمل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | وصّف المحمل لإلغاء التسجيل. |

