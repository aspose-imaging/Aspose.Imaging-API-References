---
title: "ImageCreatorsRegistry فئة"
type: docs
weight: 5690
url: /ar/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | يحصل على الوصّفات المسجّلة. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | يحصل على صيغ إنشاء الصور المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | ينشئ أول منشئ تم العثور عليه مناسب للمحدد. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | يحصل على أول موصّف مدعوم تم العثور عليه مناسب للمحدد. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | يسجّل موصّف منشئ الصورة المحدد. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | يسجّل المنشئ. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | يلغي تسجيل المنشئ. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

ينشئ أول منشئ تم العثور عليه مناسب للمحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | المنشئ الذي يدعم المحدد أو null إذا لم يُعثر على منشئ مماثل. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

يحصل على أول موصّف مدعوم تم العثور عليه مناسب للمحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | خيارات الصورة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | موصّف المنشئ الذي يدعم المحدد أو null إذا لم يُعثر على موصّف مماثل. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

يسجّل موصّف منشئ الصورة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | موصّف منشئ الصورة. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

يسجّل المنشئ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | موصّف المنشئ للتسجيل. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

يلغي تسجيل المنشئ.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | موصّف المنشئ. |

