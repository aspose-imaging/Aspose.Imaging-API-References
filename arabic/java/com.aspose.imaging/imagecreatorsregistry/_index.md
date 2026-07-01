---
title: "ImageCreatorsRegistry"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سجل منشئي الصور."
type: docs
weight: 58
url: /ar/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

يمثل سجل منشئي الصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | يحصل على صيغ إنشاء الصور المسجلة. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | يحصل على الوصفات المسجلة. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | يسجل موصّف منشئ الصورة المحدد. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | يحصل على أول موصّف مدعوم تم العثور عليه مناسب للمحدد. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | ينشئ أول منشئ تم العثور عليه مناسب للمحدد. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | يسجل المنشئ. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | يلغي تسجيل المنشئ. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


يحصل على صيغ إنشاء الصور المسجلة.

القيمة: صيغ إنشاء الصور المسجلة.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


يحصل على الوصفات المسجلة.

القيمة: الوصفيات المسجلة.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


يسجل موصّف منشئ الصورة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | موصّف منشئ الصورة. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


يحصل على أول موصّف مدعوم تم العثور عليه مناسب للمحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الصورة. |

الموصّف الأول للمنشئ سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


ينشئ أول منشئ تم العثور عليه مناسب للمحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الصورة. |

المنشئ الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


يسجل المنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | موصّف المنشئ للتسجيل. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


يلغي تسجيل المنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | موصّف المنشئ. |

