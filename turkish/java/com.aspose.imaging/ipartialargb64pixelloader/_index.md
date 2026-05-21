---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "64-bit ARGB piksel yükleyicisi."
type: docs
weight: 142
url: /tr/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64-bit ARGB piksel yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Yüklenen pikselleri işler. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Yüklenen pikselleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Piksel dikdörtgeni. |
| pikseller | long[] | 64 bitlik ARGB pikselleri. |
| start | [Point](../../com.aspose.imaging/point) | Başlangıç piksel noktası. (sol,üst) ile eşit değilse, tam bir dikdörtgen olmadığını gösterir. |
| end | [Point](../../com.aspose.imaging/point) | Bitiş piksel noktası. (sağ,alt) ile eşit değilse, tam bir dikdörtgen olmadığını gösterir. |

