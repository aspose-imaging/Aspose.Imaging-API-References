---
title: JpegOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает параметры JPEG используемые для создания или загрузки этого экземпляраJpegImageaspose.imaging.fileformats.jpeg/jpegimage.
type: docs
weight: 130
url: /ru/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

Получает параметры JPEG, используемые для создания или загрузки этого экземпляра[`JpegImage`](../../jpegimage).

```csharp
public JpegOptions JpegOptions { get; }
```

### Стоимость имущества

Параметры JPEG.

### Примеры

В следующем примере показано, как извлечь информацию заголовка из изображения JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

 // Вывод выглядит так: 
 //Количество бит на канал: 8
 // Максимально допустимый размер для всех внутренних буферов: 0
 // Тип цвета: YCbCr
 //Тип сжатия: Baseline
 //Качество изображения: 75
 //Выборка для компонента 0: 1x1
//Выборка для компонента 1: 1x1
//Выборка для компонента 2: 1x1
```

### Смотрите также

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* пространство имен [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->