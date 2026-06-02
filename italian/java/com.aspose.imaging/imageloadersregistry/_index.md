---
title: "ImageLoadersRegistry"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il registro dei caricatori di immagini."
type: docs
weight: 61
url: /it/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Rappresenta il registro dei caricatori di immagini.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ottiene i formati di caricamento immagine registrati. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Ottiene i descrittori registrati. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Registra il descrittore del caricatore immagine specificato. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Ottiene il primo descrittore supportato per nome del tipo. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Ottiene il primo formato file supportato per nome del tipo. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Ottiene il primo descrittore supportato trovato adatto per lo `stream` specificato e, opzionalmente, per le `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Crea il primo loader trovato adatto al `stream` specificato e facoltativamente alle `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Registra il loader. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Annulla la registrazione del loader. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ottiene i formati di caricamento immagine registrati.

Valore: i formati di caricamento delle immagini registrati.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Ottiene i descrittori registrati.

Valore: i descrittori registrati.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Registra il descrittore del caricatore immagine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Il descrittore del loader immagine. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Ottiene il primo descrittore supportato per nome del tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Il nome del tipo di descrittore. |

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Ottiene il primo formato file supportato per nome del tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | long | Il formato file del descrittore supportato. |

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Ottiene il primo descrittore supportato trovato adatto per lo `stream` specificato e, opzionalmente, per le `loadOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Crea il primo loader trovato adatto al `stream` specificato e facoltativamente alle `loadOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

Il primo loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registra il loader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Il descrittore del loader da registrare. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Annulla la registrazione del loader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Il descrittore del loader da deregistrare. |

