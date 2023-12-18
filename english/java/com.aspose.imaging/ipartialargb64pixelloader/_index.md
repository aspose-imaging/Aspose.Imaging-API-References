---
title: IPartialArgb64PixelLoader
second_title: Aspose.Imaging for Java API Reference
description: The 64-bit ARGB pixels loader.
type: docs
weight: 142
url: /java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

The 64-bit ARGB pixels loader.
## Methods

| Method | Description |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Processes the loaded pixels. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The pixels rectangle. |
| pixels | long[] | The 64-bit ARGB pixels. |
| start | [Point](../../com.aspose.imaging/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

