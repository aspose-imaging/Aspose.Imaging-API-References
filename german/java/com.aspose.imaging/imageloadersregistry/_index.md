---
title: "ImageLoadersRegistry"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Register der Bild‑Lader dar."
type: docs
weight: 61
url: /de/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Stellt das Register der Bild‑Lader dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Liest die registrierten Bildladeformate. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Liest die registrierten Deskriptoren. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Registriert den angegebenen Bildlader-Deskriptor. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Liest den ersten unterstützten Deskriptor anhand seines Typnamens. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Liest das erste unterstützte Dateiformat anhand seines Typnamens. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Liest den zuerst gefundenen unterstützten Deskriptor, der für den angegebenen `stream` geeignet ist und optional die `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Erstellt den zuerst gefundenen Loader, der für den angegebenen `stream` geeignet ist, und optional die `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Registriert den Loader. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Meldet den Loader ab. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Liest die registrierten Bildladeformate.

Wert: Die registrierten Bildladeformate.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Liest die registrierten Deskriptoren.

Wert: Die registrierten Deskriptoren.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Registriert den angegebenen Bildlader-Deskriptor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Der Bild-Loader-Deskriptor. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Liest den ersten unterstützten Deskriptor anhand seines Typnamens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Der Deskriptor-Typname. |

Der erste Loader-Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Liest das erste unterstützte Dateiformat anhand seines Typnamens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileFormat | long | Das unterstützte Deskriptor-Dateiformat. |

Der erste Loader-Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Liest den zuerst gefundenen unterstützten Deskriptor, der für den angegebenen `stream` geeignet ist und optional die `loadOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

Der erste Loader-Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Erstellt den zuerst gefundenen Loader, der für den angegebenen `stream` geeignet ist, und optional die `loadOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

Der erste Loader wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registriert den Loader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Der zu registrierende Loader-Deskriptor. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Meldet den Loader ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Der zu deregistrierende Loader-Deskriptor. |

