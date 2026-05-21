---
title: "ImageLoadersRegistry"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar registret för bildladdare."
type: docs
weight: 61
url: /sv/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Representerar registret för bildladdare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Hämtar de registrerade bildladdningsformaten. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivarna. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Registrerar den angivna bildladdarbeskrivaren. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Hämtar det första stödjade filformatet efter dess typnamn. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Hämtar den först hittade stödjade beskrivaren som passar den angivna `stream` och eventuellt `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Skapar den först hittade laddaren som är lämplig för den angivna `stream` och eventuellt `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Registrerar laddaren. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Avregistrerar laddaren. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Hämtar de registrerade bildladdningsformaten.

Värde: De registrerade bildladdningsformaten.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivarna.

Värde: De registrerade beskrivarna.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Registrerar den angivna bildladdarbeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Bildladdarens beskrivare. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Hämtar den första stödjade beskrivaren efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Beskrivartypens namn. |

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Hämtar det första stödjade filformatet efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | long | Det stödjade filformatet för beskrivaren. |

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Hämtar den först hittade stödjade beskrivaren som passar den angivna `stream` och eventuellt `loadOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Skapar den först hittade laddaren som är lämplig för den angivna `stream` och eventuellt `loadOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

Den första laddaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registrerar laddaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Laddarbeskrivaren att registrera. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Avregistrerar laddaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Laddarbeskrivaren att avregistrera. |

