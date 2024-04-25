---
title: ImageCreatorsRegistry
second_title: Aspose.Imaging for Java API Reference
description: Represents the image creators registry.
type: docs
weight: 58
url: /com.aspose.imaging/imagecreatorsregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Represents the image creators registry.
## Methods

| Method | Description |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Gets the registered image creation formats. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Gets the registered descriptors. |
| [register(IImageCreatorDescriptor creatorDescriptor)](#register-com.aspose.imaging.IImageCreatorDescriptor-) | Registers the specified image creator descriptor. |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-) | Gets the fist found supported descriptor suitable for the specified. |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-) | Creates the first found creator suitable for the specified. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Registers the creator. |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-) | Unregisters the creator. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Gets the registered image creation formats.

Value: The registered image creation formats.

**Returns:**
long
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Gets the registered descriptors.

Value: The registered descriptors.

**Returns:**
com.aspose.imaging.IImageCreatorDescriptor[]
### register(IImageCreatorDescriptor creatorDescriptor) {#register-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor creatorDescriptor)
```


Registers the specified image creator descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | The image creator descriptor. |

### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Gets the fist found supported descriptor suitable for the specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The image options.

The first creator descriptor will be actually the last registered. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Creates the first found creator suitable for the specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The image options.

The first creator will be actually the last registered. |

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registers the creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | The creator descriptor to register. |

### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.imaging.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Unregisters the creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.imaging/iimagecreatordescriptor) | The creator descriptor. |

