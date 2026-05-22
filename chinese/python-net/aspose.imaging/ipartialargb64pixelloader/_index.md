---
title: "IPartialArgb64PixelLoader 类"
type: docs
weight: 5510
url: /zh/python-net/aspose.imaging/ipartialargb64pixelloader/
---

**Summary:** The 64-bit ARGB pixels loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialArgb64PixelLoader

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [process64(pixels_rectangle, pixels, start, end)](#process64_pixels_rectangle_pixels_start_end_1) | 处理已加载的像素。 |


### Method: process64(pixels_rectangle, pixels, start, end) {#process64_pixels_rectangle_pixels_start_end_1}


```
 process64(pixels_rectangle, pixels, start, end) 
```

处理已加载的像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 像素矩形。 |
| 像素 | int[] | 64 位 ARGB 像素。 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

