---
title: SetPixel
second_title: Справочник по Aspose.Imaging for .NET API
description: Устанавливает пиксель изображения для указанной позиции.
type: docs
weight: 570
url: /ru/net/aspose.imaging/rasterimage/setpixel/
---
## RasterImage.SetPixel method

Устанавливает пиксель изображения для указанной позиции.

```csharp
public void SetPixel(int x, int y, Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Местоположение пикселя x. |
| y | Int32 | Местоположение пикселя y. |
| color | Color | Цвет пикселя для указанной позиции. |

### Примеры

В следующем примере загружается растровое изображение и задается цвет произвольного пикселя.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

     // Устанавливает цвет верхнего левого пикселя.
    rasterImage.SetArgb32Pixel(0, 0, Aspose.Imaging.Color.Aqua.ToArgb());

     // Другой способ — передать экземпляр Aspose.Imaging.Color сразу
    rasterImage.SetPixel(0, 0, Aspose.Imaging.Color.Aqua);
}
```

### Смотрите также

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->