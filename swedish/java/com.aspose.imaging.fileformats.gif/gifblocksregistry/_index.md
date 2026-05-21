---
title: "GifBlocksRegistry"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar registret för gif-blockens öppnare."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.gif/gifblocksregistry/
---
**Inheritance:**
java.lang.Object
```
public final class GifBlocksRegistry
```

Representerar registret för gif-blockens öppnare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivarna. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) |  |
| [loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)](#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-) |  |
| [registerOpener(IGifBlockLoaderDescriptor openerDescriptor)](#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Registrerar öppnaren. |
| [unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)](#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Avregistrerar öppnaren. |
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IGifBlockLoaderDescriptor[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivarna.

Värde: De registrerade beskrivarna.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor[]
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Hämtar den första stödjade beskrivaren efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Beskrivartypens namn. |

Den första öppnardeskriptorn kommer faktiskt att vara den sista registrerade. |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptor(InputStream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream |  |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor)
### loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette) {#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-}
```
public static IGifBlock loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream |  |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) |  |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
### registerOpener(IGifBlockLoaderDescriptor openerDescriptor) {#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void registerOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Registrerar öppnaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | Öppnardeskriptorn att registrera. |

### unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor) {#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Avregistrerar öppnaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | Öppnardeskriptorn att avregistrera. |

