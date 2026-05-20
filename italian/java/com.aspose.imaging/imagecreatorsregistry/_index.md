---
title: "ImageCreatorsRegistry"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il registro dei creatori di immagini."
type: docs
weight: 58
url: /it/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Rappresenta il registro dei creatori di immagini.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Restituisce i formati di creazione immagine registrati. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Ottiene i descrittori registrati. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Registra il descrittore del creatore di immagini specificato. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Ottiene il primo descrittore supportato trovato adatto a quello specificato. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Crea il primo creatore trovato adatto a quello specificato. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Registra il creatore. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Annulla la registrazione del creatore. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Restituisce i formati di creazione immagine registrati.

Valore: i formati di creazione immagine registrati.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Ottiene i descrittori registrati.

Valore: i descrittori registrati.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Registra il descrittore del creatore di immagini specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Il descrittore del creatore di immagini. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Ottiene il primo descrittore supportato trovato adatto a quello specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni dell'immagine. |

Il primo descrittore del creatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Crea il primo creatore trovato adatto a quello specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni dell'immagine. |

Il primo creatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registra il creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Il descrittore del creatore da registrare. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Annulla la registrazione del creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Il descrittore del creatore. |

