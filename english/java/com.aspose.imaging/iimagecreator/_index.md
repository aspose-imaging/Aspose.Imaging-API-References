---
title: IImageCreator
second_title: Aspose.Imaging for Java API Reference
description: The image creator.
type: docs
weight: 127
url: /java/com.aspose.imaging/iimagecreator/
---```
public interface IImageCreator
```

The image creator.
## Methods

| Method | Description |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.StreamContainer-com.aspose.imaging.ImageOptionsBase-int-int-) | Creates a new image instance with `imageOptions`. |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.StreamContainer-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


Creates a new image instance with `imageOptions`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container to create image data in. |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The image options. |
| width | int | width of new image |
| height | int | height of new image |

**Returns:**
[Image](../../com.aspose.imaging/image) - A new image instance.
