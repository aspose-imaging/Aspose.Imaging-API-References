---
title: "ImageLoadersRegistry"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü yükleyiciler kayıt defterini temsil eder."
type: docs
weight: 61
url: /tr/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Görüntü yükleyiciler kayıt defterini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Kayıtlı görüntü yükleme biçimlerini alır. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Kayıtlı tanımlayıcıları alır. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Belirtilen görüntü yükleyici tanımlayıcısını kaydeder. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Tür adıyla ilk desteklenen tanımlayıcıyı alır. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Tür adıyla ilk desteklenen dosya biçimini alır. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Belirtilen `stream` için uygun ve isteğe bağlı olarak `loadOptions` ile ilk bulunan desteklenen tanımlayıcıyı alır. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Belirtilen `stream` için uygun olan ilk bulunan yükleyiciyi ve isteğe bağlı olarak `loadOptions` öğesini oluşturur. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Yükleyiciyi kaydeder. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Yükleyicinin kaydını siler. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Kayıtlı görüntü yükleme biçimlerini alır.

Değer: Kayıtlı görüntü yükleme biçimleri.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Kayıtlı tanımlayıcıları alır.

Değer: Kayıtlı tanımlayıcılar.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Belirtilen görüntü yükleyici tanımlayıcısını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Görüntü yükleyici tanımlayıcısı. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Tür adıyla ilk desteklenen tanımlayıcıyı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Tanımlayıcı tür adı. |

İlk yükleyici tanımlayıcısı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Tür adıyla ilk desteklenen dosya biçimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | long | Desteklenen tanımlayıcı dosya biçimi. |

İlk yükleyici tanımlayıcısı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Belirtilen `stream` için uygun ve isteğe bağlı olarak `loadOptions` ile ilk bulunan desteklenen tanımlayıcıyı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

İlk yükleyici tanımlayıcısı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Belirtilen `stream` için uygun olan ilk bulunan yükleyiciyi ve isteğe bağlı olarak `loadOptions` öğesini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

İlk yükleyici aslında son kaydedilen olacaktır. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Yükleyiciyi kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Kayıt edilecek yükleyici tanımlayıcısı. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Yükleyicinin kaydını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Kayıt silinecek yükleyici tanımlayıcısı. |

