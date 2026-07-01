---
title: "ImageLoadersRegistry"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سجل محملات الصور."
type: docs
weight: 61
url: /ar/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

يمثل سجل محملات الصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | يحصل على صيغ تحميل الصور المسجلة. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | يحصل على الوصفات المسجلة. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | يسجل وصف محمل الصورة المحدد. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | يحصل على الوصف الأول المدعوم حسب اسم النوع الخاص به. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | يحصل على صيغة الملف الأولى المدعومة حسب اسم النوع الخاص بها. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | يحصل على الوصف الأول المدعوم الذي تم العثور عليه والمناسب لـ `stream` المحدد وباختياري `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | ينشئ أول محمل تم العثور عليه مناسب للـ `stream` المحدد، وبشكل اختياري `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | يسجل المحمل. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | يلغي تسجيل المحمل. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


يحصل على صيغ تحميل الصور المسجلة.

القيمة: صيغ تحميل الصور المسجلة.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


يحصل على الوصفات المسجلة.

القيمة: الوصفيات المسجلة.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


يسجل وصف محمل الصورة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | وصف محمل الصورة. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


يحصل على الوصف الأول المدعوم حسب اسم النوع الخاص به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | اسم نوع الوصف. |

وصف المحمل الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


يحصل على صيغة الملف الأولى المدعومة حسب اسم النوع الخاص بها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | long | صيغة ملف الوصف المدعومة. |

وصف المحمل الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


يحصل على الوصف الأول المدعوم الذي تم العثور عليه والمناسب لـ `stream` المحدد وباختياري `loadOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

وصف المحمل الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


ينشئ أول محمل تم العثور عليه مناسب للـ `stream` المحدد، وبشكل اختياري `loadOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

المحمل الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


يسجل المحمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | وصف المحمل للتسجيل. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


يلغي تسجيل المحمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | وصف المحمل لإلغاء التسجيل. |

