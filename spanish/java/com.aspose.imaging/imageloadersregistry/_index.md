---
title: "ImageLoadersRegistry"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el registro de cargadores de imágenes."
type: docs
weight: 61
url: /es/java/com.aspose.imaging/imageloadersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Representa el registro de cargadores de imágenes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtiene los formatos de carga de imágenes registrados. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtiene los descriptores registrados. |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.imaging.IImageLoaderDescriptor-) | Registra el descriptor de cargador de imágenes especificado. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Obtiene el primer formato de archivo compatible por su nombre de tipo. |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Obtiene el primer descriptor compatible encontrado adecuado para el `stream` especificado y, opcionalmente, los `loadOptions`. |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Crea el primer cargador encontrado adecuado para el `stream` especificado y opcionalmente las `loadOptions`. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Registra el cargador. |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-) | Desregistra el cargador. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtiene los formatos de carga de imágenes registrados.

Valor: Los formatos de carga de imagen registrados.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Obtiene los descriptores registrados.

Valor: Los descriptores registrados.

**Returns:**
com.aspose.imaging.IImageLoaderDescriptor[]
### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Registra el descriptor de cargador de imágenes especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | El descriptor del cargador de imagen. |

### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Obtiene el primer descriptor compatible por su nombre de tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | El nombre del tipo de descriptor. |

El primer descriptor de cargador será en realidad el último registrado. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Obtiene el primer formato de archivo compatible por su nombre de tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileFormat | long | El formato de archivo de descriptor compatible. |

El primer descriptor de cargador será en realidad el último registrado. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Obtiene el primer descriptor compatible encontrado adecuado para el `stream` especificado y, opcionalmente, los `loadOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

El primer descriptor de cargador será en realidad el último registrado. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) - The loader descriptor which supports the specified `stream` and `loadOptions` or null if no such descriptor is found.
### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Crea el primer cargador encontrado adecuado para el `stream` especificado y opcionalmente las `loadOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
|  | loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

El primer cargador será en realidad el último registrado. |

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - The loader which supports the specified `stream` and `loadOptions` or null if no such loader is found.
### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registra el cargador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | El descriptor del cargador a registrar. |

### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.imaging.IImageLoaderDescriptor-}
```
public static synchronized void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Desregistra el cargador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.imaging/iimageloaderdescriptor) | El descriptor del cargador a desregistrar. |

