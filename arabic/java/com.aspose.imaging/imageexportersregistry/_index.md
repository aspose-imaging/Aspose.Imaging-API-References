---
title: "ImageExportersRegistry"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سجل مصدري الصور."
type: docs
weight: 59
url: /ar/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

يمثل سجل مصدري الصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | يحصل على صيغ التصدير المسجلة. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | يحصل على أوصاف المصدر المسجلة. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | يسجل وصف المصدر الصورة المحدد. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | يحصل على الوصف المدعوم الأول الذي تم العثور عليه المناسب لخيارات الحفظ المحددة والصورة. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | ينشئ المصدر الأول الذي تم العثور عليه المناسب لخيارات الحفظ المحددة والصورة. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | يسجل المصدر. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | يلغي تسجيل المصدر. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


يحصل على صيغ التصدير المسجلة.

القيمة: صيغ التصدير المسجلة.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


يحصل على أوصاف المصدر المسجلة.

القيمة: أوصاف المصدر المسجلة.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


يسجل وصف المصدر الصورة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | وصف مصدر الصورة. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


يحصل على الوصف المدعوم الأول الذي تم العثور عليه المناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة المراد تصديرها. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات. |

وصف المصدر الأول سيكون في الواقع الأخير المسجل. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


ينشئ المصدر الأول الذي تم العثور عليه المناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة المراد تصديرها. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الحفظ التي يجب استخدامها للتصدير. |

المصدّر الأول سيكون في الواقع الأخير المسجّل. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


يسجل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | وصف المصدّر لتسجيله. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


يلغي تسجيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | وصف المصدّر لإلغاء تسجيله. |

