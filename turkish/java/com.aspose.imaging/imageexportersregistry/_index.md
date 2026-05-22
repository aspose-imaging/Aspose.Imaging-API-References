---
title: "ImageExportersRegistry"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü dışa aktarıcılar kayıt defterini temsil eder."
type: docs
weight: 59
url: /tr/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Görüntü dışa aktarıcılar kayıt defterini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Kayıtlı dışa aktarma formatlarını alır. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Kayıtlı dışa aktarıcı tanımlayıcılarını alır. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk dışa aktarıcıyı oluşturur. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Dışa aktarıcıyı kaydeder. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Dışa aktarıcının kaydını siler. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Kayıtlı dışa aktarma formatlarını alır.

Değer: Kayıtlı dışa aktarma formatları.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Kayıtlı dışa aktarıcı tanımlayıcılarını alır.

Değer: Kayıtlı dışa aktarıcı tanımlayıcıları.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Görüntü dışa aktarıcı tanımlayıcısı. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dışa aktarılacak görüntü. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçenekler. |

İlk dışa aktarıcı tanımlayıcısı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk dışa aktarıcıyı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dışa aktarılacak görüntü. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Dışa aktarma için kullanılacak kaydetme seçenekleri. |

İlk dışa aktarıcı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Dışa aktarıcıyı kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Kaydedilecek dışa aktarıcı tanımlayıcısı. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Dışa aktarıcının kaydını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Kaldırılacak dışa aktarıcı tanımlayıcısı. |

