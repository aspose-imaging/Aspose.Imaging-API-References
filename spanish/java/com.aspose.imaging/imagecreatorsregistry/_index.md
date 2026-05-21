---
title: "ImageCreatorsRegistry"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el registro de creadores de imágenes."
type: docs
weight: 58
url: /es/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Representa el registro de creadores de imágenes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtiene los formatos de creación de imágenes registrados. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtiene los descriptores registrados. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Registra el descriptor del creador de imagen especificado. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Obtiene el primer descriptor compatible encontrado adecuado para lo especificado. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Crea el primer creador encontrado adecuado para lo especificado. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Registra el creador. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Anula el registro del creador. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtiene los formatos de creación de imágenes registrados.

Valor: Los formatos de creación de imagen registrados.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Obtiene los descriptores registrados.

Valor: Los descriptores registrados.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Registra el descriptor del creador de imagen especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | El descriptor del creador de imagen. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Obtiene el primer descriptor compatible encontrado adecuado para lo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones de imagen. |

El primer descriptor del creador será, en realidad, el último registrado. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Crea el primer creador encontrado adecuado para lo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones de imagen. |

El primer creador será, en realidad, el último registrado. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registra el creador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | El descriptor del creador a registrar. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Anula el registro del creador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | El descriptor del creador. |

