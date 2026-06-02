---
title: "IPartialArgb32PixelLoader 类"
type: docs
weight: 5500
url: /zh/python-net/aspose.imaging/ipartialargb32pixelloader/
---

**Summary:** Conforms to the 32-bit ARGB pixels loaded partially.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialArgb32PixelLoader

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | 处理已加载的像素。 |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

处理已加载的像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 像素矩形。 |
| 像素 | int[] | 32 位 ARGB 像素。 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

