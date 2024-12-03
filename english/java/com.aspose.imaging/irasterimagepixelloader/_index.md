---
title: IRasterImagePixelLoader
second_title: Aspose.Imaging for Java API Reference
description: The raster image pixel loader.
type: docs
weight: 147
url: /java/com.aspose.imaging/irasterimagepixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageRawDataLoader](../../com.aspose.imaging/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

The raster image pixel loader.
## Methods

| Method | Description |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Loads pixels partially (by blocks). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Loads pixels partially (by blocks).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | The partial loader. |

