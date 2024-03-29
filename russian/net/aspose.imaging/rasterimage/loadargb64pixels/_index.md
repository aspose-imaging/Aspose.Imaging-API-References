---
title: LoadArgb64Pixels
second_title: Справочник по Aspose.Imaging for .NET API
description: Загружает 64-битные пиксели ARGB.
type: docs
weight: 370
url: /ru/net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

Загружает 64-битные пиксели ARGB.

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник, из которого загружаются пиксели. |

### Возвращаемое значение

Загруженный массив 64-битных пикселей ARGB.

### Примеры

В следующем примере показано, как загружать и обрабатывать пиксели растрового изображения. Пиксели представлены как 64-битные целочисленные значения. Например, рассмотрим задачу подсчета полностью прозрачных пикселей изображения.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Загрузить пиксели для всего изображения. В качестве параметра метода Aspose.Imaging.RasterImage.LoadArgb64Pixels можно указать любую прямоугольную часть изображения.
    // Обратите внимание, что само изображение должно иметь 16 бит на выборку, потому что Aspose.Imaging.RasterImage.LoadArgb64Pixels не работает с 8 битами на выборку.
    // Для работы с 8 битами на выборку используйте старый добрый метод Aspose.Imaging.RasterImage.LoadArgb32Pixels.
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        // Обратите внимание, что все компоненты цвета, включая альфа, представлены 16-битными значениями, поэтому их допустимые значения находятся в диапазоне [0, 63535].
        int alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

### Смотрите также

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
