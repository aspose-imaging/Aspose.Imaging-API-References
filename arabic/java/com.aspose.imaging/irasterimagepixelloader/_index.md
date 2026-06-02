---
title: "IRasterImagePixelLoader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "محمل بكسلات الصورة النقطية."
type: docs
weight: 147
url: /ar/java/com.aspose.imaging/irasterimagepixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageRawDataLoader](../../com.aspose.imaging/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

محمل بكسلات الصورة النقطية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | يقوم بتحميل البكسلات جزئياً (حسب الكتل). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


يقوم بتحميل البكسلات جزئياً (حسب الكتل).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل لتحميل البكسلات منه. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | المحمّل الجزئي. |

