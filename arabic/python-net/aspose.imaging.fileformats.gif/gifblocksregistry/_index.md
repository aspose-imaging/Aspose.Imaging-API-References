---
title: "GifBlocksRegistry فئة"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | يحصل على الوصّفات المسجّلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | يحصل على أول مُوصف مُفتاح مدعوم. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | يحصل على أول وصّف مدعوم بحسب اسم النوع الخاص به. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | يحمّل كتلة GIF باستخدام أول مُفتاح تم العثور عليه المناسب للمُدَخل _stream_ المحدد. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | يسجّل المفتاح. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | يلغي تسجيل المفتاح. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

يحصل على أول مُوصف مُفتاح مدعوم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | مُوصف مُفتاح كتلة GIF أو null إذا لم يكن هناك مُوصف مفتاح مدعوم لهذا المُدَخل. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | أول مُوصف مفتاح تم العثور عليه أو null إذا لم يُعثر على مثل هذا المُوصف. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

يحمّل كتلة GIF باستخدام أول مُفتاح تم العثور عليه المناسب للمُدَخل _stream_ المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة ألوان الحاوية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | كتلة GIF المحمّلة أو null إذا لم يُعثر على أي مفتاح. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

يسجّل المفتاح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | مُوصف المفتاح للتسجيل. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

يلغي تسجيل المفتاح.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | مُوصف المفتاح لإلغاء التسجيل. |

