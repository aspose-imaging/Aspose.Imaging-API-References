---
title: "ImageLoadersRegistry"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سجل محمّلات الصور."
type: docs
weight: 61
url: /ar/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

يمثل سجل محمّلات الصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | يحصل على صيغ تحميل الصور المسجلة. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | يحصل على الوصفيات المسجلة. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | يسجل وصيفة محمل الصورة المحددة. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | يحصل على أول وصيفة مدعومة باسم نوعها. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | يحصل على أول صيغة ملف مدعومة باسم نوعها. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | يحصل على أول وصيفة مدعومة تم العثور عليها مناسبة للـ `stream` المحدد وباختياري `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | ينشئ أول محمل يتم العثور عليه مناسب للمحدد `stream` و`loadOptions` اختياريًا. |
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


يحصل على الوصفيات المسجلة.

القيمة: الوصفيات المسجلة.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


يسجل وصيفة محمل الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | وصف محمل الصورة. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


يحصل على أول وصيفة مدعومة باسم نوعها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | اسم نوع الوصف. |

وصف أول محمل سيكون فعليًا آخر محمل تم تسجيله. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


يحصل على أول صيغة ملف مدعومة باسم نوعها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileFormat | long | صيغة ملف الوصف المدعومة. |

وصف أول محمل سيكون فعليًا آخر محمل تم تسجيله. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


يحصل على أول وصيفة مدعومة تم العثور عليها مناسبة للـ `stream` المحدد وباختياري `loadOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

وصف أول محمل سيكون فعليًا آخر محمل تم تسجيله. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


ينشئ أول محمل يتم العثور عليه مناسب للمحدد `stream` و`loadOptions` اختياريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

أول محمل سيكون فعليًا آخر محمل تم تسجيله. |

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

