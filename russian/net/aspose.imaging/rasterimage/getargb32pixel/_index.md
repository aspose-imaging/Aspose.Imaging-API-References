---
title: GetArgb32Pixel
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает 32-битный пиксель изображения ARGB.
type: docs
weight: 280
url: /ru/net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

Получает 32-битный пиксель изображения ARGB.

```csharp
public int GetArgb32Pixel(int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Местоположение пикселя x. |
| y | Int32 | Местоположение пикселя y. |

### Возвращаемое значение

32-битный пиксель ARGB для указанного местоположения.

### Примеры

В следующем примере выполняется загрузка растрового изображения и получение цвета произвольного пикселя, представленного в виде 32-разрядного целого числа.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загружаем изображение из файла PNG.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
     // Кэшируем все пиксельные данные, чтобы не выполнялась дополнительная загрузка данных из базовых данных stream
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

     // Чтение всех пикселей выполняется довольно быстро.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

 // Загружаем изображение из PNG file
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

     // Чтение всех пикселей происходит не так быстро, как при caching
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Вывод может выглядеть так: 
 // Чтение всех кэшированных пикселей заняло 1500 мс.
// Чтение всех пикселей без предварительного кеширования заняло 150000 мс.
```

В следующем примере показано, как кэширование изображений влияет на производительность. В общем случае чтение кэшированных данных выполняется быстрее, чем чтение некэшированных данных.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Загружаем изображение из файла PNG.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
     // Кэшируем все пиксельные данные, чтобы не выполнялась дополнительная загрузка данных из базовых данных stream
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

     // Чтение всех пикселей выполняется довольно быстро.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

 // Загружаем изображение из PNG file
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

     // Чтение всех пикселей происходит не так быстро, как при caching
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Вывод может выглядеть так: 
 // Чтение всех кэшированных пикселей заняло 1500 мс.
// Чтение всех пикселей без предварительного кеширования заняло 150000 мс.
```

### Смотрите также

* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.Imaging](../../rasterimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->