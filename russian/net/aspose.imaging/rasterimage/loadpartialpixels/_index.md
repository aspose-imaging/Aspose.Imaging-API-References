---
title: LoadPartialPixels
second_title: Справочник по Aspose.Imaging for .NET API
description: Загружает пиксели частично пачками.
type: docs
weight: 400
url: /ru/net/aspose.imaging/rasterimage/loadpartialpixels/
---
## RasterImage.LoadPartialPixels method

Загружает пиксели частично пачками.

```csharp
public void LoadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| желаемыйпрямоугольник | Rectangle | Желаемый прямоугольник. |
| pixelLoader | IPartialPixelLoader | Загрузчик пикселей. |

### Примеры

В следующем примере показано, как загружать и обрабатывать пиксели растрового изображения с помощью собственного частичного процессора. Например, рассмотрим задачу подсчета полностью прозрачных пикселей изображения. Для подсчета прозрачности с использованием механизма частичной загрузки введен отдельный класс TransparentPixelCounter, реализующий Aspose.Imaging.IPartialPixelLoader.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

     // Создаем экземпляр Aspose.Imaging.IPartialPixelLoader и передаем его Aspose.Imaging.RasterImage.LoadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

     // Загрузить пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве первого параметра метода Aspose.Imaging.RasterImage.LoadPartialPixels.
    rasterImage.LoadPartialPixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

 // Счетчик может выглядеть так: 
/// <summary>
 /// Подсчитывает количество полностью прозрачных пикселей со значением альфа-канала 0.
/// </summary>
private class TransparentPixelCounter : IPartialPixelLoader
{
    /// <summary>
     /// Количество полностью прозрачных пикселей.
    /// </summary>
    private int count;

    /// <summary>
     /// Получает количество полностью прозрачных пикселей.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Обрабатывает загруженные пиксели. Этот метод вызывается каждый раз, когда загружается новая порция пикселей.
    /// </summary>
     /// <param name="pixelsRectangle">Прямоугольник в пикселях.</param>
     /// <param name="pixels">32-битные пиксели ARGB.</param>
     /// <param name="start">Точка начального пикселя.</param>
     /// <param name="end">Конечная точка пикселей.</param>
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, Aspose.Imaging.Color[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (Color pixel in pixels)
        {
            if (pixel.A == 0)
            {
                this.count++;
            }
        }
    }
}
```

### Смотрите также

* struct [Rectangle](../../rectangle)
* interface [IPartialPixelLoader](../../ipartialpixelloader)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->