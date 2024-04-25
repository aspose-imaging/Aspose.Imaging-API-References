---
title: GifBlocksRegistry
second_title: Aspose.Imaging for Java API Reference
description: Represents the gif blocks openers registry.
type: docs
weight: 12
url: /com.aspose.imaging.fileformats.gif/gifblocksregistry/
---
**Inheritance:**
java.lang.Object
```
public final class GifBlocksRegistry
```

Represents the gif blocks openers registry.
## Methods

| Method | Description |
| --- | --- |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Gets the registered descriptors. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Gets the first supported descriptor by its type name. |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) |  |
| [loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)](#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-) |  |
| [registerOpener(IGifBlockLoaderDescriptor openerDescriptor)](#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Registers the opener. |
| [unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)](#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | Unregisters the opener. |
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IGifBlockLoaderDescriptor[] getRegisteredDescriptors()
```


Gets the registered descriptors.

Value: The registered descriptors.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor[]
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Gets the first supported descriptor by its type name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | java.lang.String | The descriptor type name.

The first opener descriptor will be actually the last registered. |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptor(InputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream |  |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor)
### loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette) {#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-}
```
public static IGifBlock loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream |  |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) |  |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
### registerOpener(IGifBlockLoaderDescriptor openerDescriptor) {#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void registerOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Registers the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The opener descriptor to register. |

### unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor) {#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


Unregisters the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The opener descriptor to unregister. |

