---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.Imaging for Java API 参考"
description: "64 位 ARGB 像素加载器。"
type: docs
weight: 142
url: /zh/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64 位 ARGB 像素加载器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | 处理已加载的像素。 |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


处理已加载的像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 像素矩形。 |
| 像素 | long[] | 64 位 ARGB 像素。 |
| start | [Point](../../com.aspose.imaging/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](../../com.aspose.imaging/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

