---
title: IPartialPixelLoader
second_title: Aspose.Imaging for Java API Reference
description: Conforms to the pixels loaded partially.
type: docs
weight: 143
url: /java/com.aspose.imaging/ipartialpixelloader/
---```
public interface IPartialPixelLoader
```

Conforms to the pixels loaded partially.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Processes the loaded pixels. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The pixels rectangle. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | The pixels. |
| start | [Point](../../com.aspose.imaging/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

