---
title: "ImageCreatorsRegistry"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Register der Bild‑Ersteller dar."
type: docs
weight: 58
url: /de/java/com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Stellt das Register der Bild‑Ersteller dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ruft die registrierten Bild-Erstellungsformate ab. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Liest die registrierten Deskriptoren. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Registriert den angegebenen Bild‑Ersteller‑Deskriptor. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Erstellt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Registriert den Ersteller. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Meldet den Ersteller ab. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ruft die registrierten Bild-Erstellungsformate ab.

Wert: Die registrierten Bild‑Erstellungsformate.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Liest die registrierten Deskriptoren.

Wert: Die registrierten Deskriptoren.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Registriert den angegebenen Bild‑Ersteller‑Deskriptor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Der Bild‑Ersteller‑Deskriptor. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Bildoptionen. |

Der erste Ersteller‑Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Erstellt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Bildoptionen. |

Der erste Ersteller wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registriert den Ersteller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Der zu registrierende Ersteller‑Deskriptor. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Meldet den Ersteller ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | Der Ersteller‑Deskriptor. |

