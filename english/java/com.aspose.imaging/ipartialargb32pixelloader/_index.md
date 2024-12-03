---
title: IPartialArgb32PixelLoader
second_title: Aspose.Imaging for Java API Reference
description: Conforms to the 32-bit ARGB pixels loaded partially.
type: docs
weight: 141
url: /java/com.aspose.imaging/ipartialargb32pixelloader/
---```
public interface IPartialArgb32PixelLoader
```

Conforms to the 32-bit ARGB pixels loaded partially.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Processes the loaded pixels. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The pixels rectangle. |
| pixels | int[] | The pixels in argb format |
| start | [Point](../../com.aspose.imaging/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

