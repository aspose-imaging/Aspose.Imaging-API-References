---
title: "IRasterImagePixelLoader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Загрузчик пикселей растрового изображения."
type: docs
weight: 147
url: /ru/java/com.aspose.imaging/irasterimagepixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageRawDataLoader](../../com.aspose.imaging/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Загрузчик пикселей растрового изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Загружает пиксели частично (по блокам). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Загружает пиксели частично (по блокам).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Частичный загрузчик. |

