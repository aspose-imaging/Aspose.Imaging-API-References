---
title: Version
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает версию файла psd.
type: docs
weight: 100
url: /ru/net/aspose.imaging.imageoptions/psdoptions/version/
---
## PsdOptions.Version property

Получает или задает версию файла psd.

```csharp
public int Version { get; set; }
```

### Стоимость имущества

Версия файла psd.

### Примеры

В этом примере показано, как сохранить изображение PNG в формате PSD с использованием различных опций, специфичных для PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
     // Определяем линейный сине-прозрачный градиент.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем PNG-изображение линейным сине-прозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

     // Следующие параметры будут использоваться для сохранения изображения PNG в формате PSD.
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

     // Количество бит на канал
    saveOptions.ChannelBitsCount = 8;

     // Количество каналов. Один канал для каждого цветового компонента R,G,B,A
    saveOptions.ChannelsCount = 4;

     // Цвет mode
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

     // Без сжатия
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

     // Версия по умолчанию 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // Сжатие RLE позволяет уменьшить размер вывода image
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // Вывод может выглядеть так: 
     // Размер изображения PSD со сжатием RAW: 40090
     // Размер PSD-изображения с RLE-сжатием: 16185
}
```

### Смотрите также

* class [PsdOptions](../../psdoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../psdoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->