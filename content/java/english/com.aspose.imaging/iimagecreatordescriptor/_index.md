---
title: IImageCreatorDescriptor
second_title: Aspose.Imaging for Java API Reference
description: The image creator descriptor specifying the creator properties.
type: docs
weight: 129
url: /com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome the necessity to contain each image creator instance in memory and multithreading issues.
## Methods

| Method | Description |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Determines whether image creator can create a new image using the `imageOptions`. |
| [createInstance()](#createInstance--) | Creates a new creator instance. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Determines whether image creator can create a new image using the `imageOptions`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The image options. |

**Returns:**
boolean - `true` if image creator created by this descriptor can create image data using the specified `imageOptions`; otherwise, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Creates a new creator instance.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.
