---
title: "ImageCreatorsRegistry"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar registret för bildskapare."
type: docs
weight: 58
url: /sv/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Representerar registret för bildskapare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Hämtar de registrerade bildskapande formaten. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivarna. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Registrerar den angivna bildskapardeskriptorn. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Hämtar den först funna stödda deskriptorn som är lämplig för den angivna. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Skapar den först funna skaparen som är lämplig för den angivna. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Registrerar skaparen. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Avregistrerar skaparen. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Hämtar de registrerade bildskapande formaten.

Värde: De registrerade bildskapande formaten.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivarna.

Värde: De registrerade beskrivarna.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Registrerar den angivna bildskapardeskriptorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Bildskapardeskriptorn. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Hämtar den först funna stödda deskriptorn som är lämplig för den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bildalternativen. |

Den första skapardeskriptorn kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Skapar den först funna skaparen som är lämplig för den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bildalternativen. |

Den första skaparen kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registrerar skaparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Skapardeskriptorn att registrera. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Avregistrerar skaparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Skapardeskriptorn. |

