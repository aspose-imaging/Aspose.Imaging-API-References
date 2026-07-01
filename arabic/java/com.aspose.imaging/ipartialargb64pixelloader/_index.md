---
title: "IPartialArgb64PixelLoader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "محمل بكسلات ARGB 64-بت."
type: docs
weight: 142
url: /ar/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

محمل بكسلات ARGB 64-بت.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | يعالج البكسلات المحمّلة. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


يعالج البكسلات المحمّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل البكسلات. |
| بكسلات | long[] | بكسلات ARGB 64-بت. |
| start | [Point](../../com.aspose.imaging/point) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| end | [Point](../../com.aspose.imaging/point) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |

