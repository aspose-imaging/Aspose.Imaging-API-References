---
title: GetPixel
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает пиксель изображения.
type: docs
weight: 330
url: /ru/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

Получает пиксель изображения.

```csharp
public Color GetPixel(int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Местоположение пикселя x. |
| y | Int32 | Местоположение пикселя y. |

### Возвращаемое значение

Цвет пикселя для указанного местоположения.

### Примеры

Следующий пример загружает растровое изображение и получает цвет произвольного пикселя.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

     // Получаем цвет верхнего левого пикселя изображения.
    Color color = rasterImage.GetPixel(0, 0);

     // Получаем значения отдельных компонентов цвета
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### Смотрите также

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->