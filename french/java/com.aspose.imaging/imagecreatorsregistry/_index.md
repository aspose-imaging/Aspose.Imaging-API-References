---
title: "ImageCreatorsRegistry"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente le registre des créateurs d'images."
type: docs
weight: 58
url: /fr/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Représente le registre des créateurs d'images.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtient les formats de création d'images enregistrés. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtient les descripteurs enregistrés. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Enregistre le descripteur de créateur d'image spécifié. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Obtient le premier descripteur pris en charge trouvé adapté au spécifié. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Crée le premier créateur trouvé adapté au spécifié. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Enregistre le créateur. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Désenregistre le créateur. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtient les formats de création d'images enregistrés.

Valeur : les formats de création d'image enregistrés.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Obtient les descripteurs enregistrés.

Valeur : les descripteurs enregistrés.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Enregistre le descripteur de créateur d'image spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Le descripteur de créateur d'image. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Obtient le premier descripteur pris en charge trouvé adapté au spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'image. |

Le premier descripteur de créateur sera en fait le dernier enregistré. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Crée le premier créateur trouvé adapté au spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'image. |

Le premier créateur sera en fait le dernier enregistré. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Enregistre le créateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Le descripteur de créateur à enregistrer. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Désenregistre le créateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Le descripteur de créateur. |

