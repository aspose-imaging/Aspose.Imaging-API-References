---
title: "GifBlocksRegistry"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Register der GIF‑Block‑Öffner dar."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.gif/gifblocksregistry/
---
**Inheritance:**
java.lang.Object
```
public final class GifBlocksRegistry
```

Stellt das Register der GIF‑Block‑Öffner dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Liest die registrierten Deskriptoren. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Liest den ersten unterstützten Deskriptor anhand seines Typnamens. |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) |  |
| [loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)](#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-) |  |
| [registerOpener(IGifBlockLoaderDescriptor openerDescriptor)](#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Registriert den Öffner. |
| [unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)](#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Deregistriert den Öffner. |
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IGifBlockLoaderDescriptor[] getRegisteredDescriptors()
```


Liest die registrierten Deskriptoren.

Wert: Die registrierten Deskriptoren.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor[]
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Liest den ersten unterstützten Deskriptor anhand seines Typnamens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Der Deskriptor-Typname. |

Der erste Öffner-Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptor(InputStream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream |  |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor)
### loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette) {#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-}
```
public static IGifBlock loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream |  |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) |  |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
### registerOpener(IGifBlockLoaderDescriptor openerDescriptor) {#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void registerOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Registriert den Öffner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | Der zu registrierende Öffner-Deskriptor. |

### unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor) {#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Deregistriert den Öffner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | Der zu deregistrierende Öffner-Deskriptor. |

