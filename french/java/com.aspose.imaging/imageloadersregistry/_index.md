---
title: "ImageLoadersRegistry"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente le registre des chargeurs d'images."
type: docs
weight: 61
url: /fr/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Représente le registre des chargeurs d'images.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtient les formats de chargement d'images enregistrés. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtient les descripteurs enregistrés. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Enregistre le descripteur de chargeur d'image spécifié. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Obtient le premier descripteur pris en charge par son nom de type. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Obtient le premier format de fichier pris en charge par son nom de type. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Obtient le premier descripteur pris en charge trouvé adapté au `stream` spécifié et éventuellement aux `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Crée le premier chargeur trouvé adapté au `stream` spécifié et éventuellement aux `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Enregistre le chargeur. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Désenregistre le chargeur. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtient les formats de chargement d'images enregistrés.

Valeur : les formats de chargement d'image enregistrés.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Obtient les descripteurs enregistrés.

Valeur : les descripteurs enregistrés.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Enregistre le descripteur de chargeur d'image spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Le descripteur du chargeur d'image. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Obtient le premier descripteur pris en charge par son nom de type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Le nom du type de descripteur. |

Le premier descripteur de chargeur sera en fait le dernier enregistré. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Obtient le premier format de fichier pris en charge par son nom de type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | long | Le format de fichier de descripteur pris en charge. |

Le premier descripteur de chargeur sera en fait le dernier enregistré. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Obtient le premier descripteur pris en charge trouvé adapté au `stream` spécifié et éventuellement aux `loadOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

Le premier descripteur de chargeur sera en fait le dernier enregistré. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Crée le premier chargeur trouvé adapté au `stream` spécifié et éventuellement aux `loadOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

Le premier chargeur sera en fait le dernier enregistré. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Enregistre le chargeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Le descripteur de chargeur à enregistrer. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Désenregistre le chargeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | Le descripteur de chargeur à désenregistrer. |

