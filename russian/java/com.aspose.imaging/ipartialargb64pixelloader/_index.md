---
title: "IPartialArgb64PixelLoader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Загрузчик 64‑битных ARGB‑пикселей."
type: docs
weight: 142
url: /ru/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Загрузчик 64‑битных ARGB‑пикселей.
## Методы

| Метод | Описание |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Обрабатывает загруженные пиксели. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Обрабатывает загруженные пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник пикселей. |
| пиксели | long[] | 64-битные ARGB пиксели. |
| start | [Point](../../com.aspose.imaging/point) | Точка начала пикселей. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.imaging/point) | Точка конца пикселей. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

