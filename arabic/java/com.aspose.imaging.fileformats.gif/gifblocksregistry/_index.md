---
title: "GifBlocksRegistry"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سجل مُفتحات كتل gif."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.gif/gifblocksregistry/
---
**Inheritance:**
java.lang.Object
```
public final class GifBlocksRegistry
```

يمثل سجل مُفتحات كتل gif.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | يحصل على الوصفيات المسجلة. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | يحصل على أول وصيفة مدعومة باسم نوعها. |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) |  |
| [loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)](#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-) |  |
| [registerOpener(IGifBlockLoaderDescriptor openerDescriptor)](#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | يسجّل الفاتح. |
| [unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)](#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | يلغي تسجيل الفاتح. |
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IGifBlockLoaderDescriptor[] getRegisteredDescriptors()
```


يحصل على الوصفيات المسجلة.

القيمة: الوصفيات المسجلة.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor[]
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


يحصل على أول وصيفة مدعومة باسم نوعها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | اسم نوع الوصف. |

المُوصِف الأول للفاتح سيكون في الواقع الأخير المسجَّل. |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptor(InputStream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream |  |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor)
### loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette) {#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-}
```
public static IGifBlock loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream |  |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) |  |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
### registerOpener(IGifBlockLoaderDescriptor openerDescriptor) {#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void registerOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


يسجّل الفاتح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | المُوصِف الفاتح لتسجيله. |

### unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor) {#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


يلغي تسجيل الفاتح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | المُوصِف الفاتح لإلغاء تسجيله. |

