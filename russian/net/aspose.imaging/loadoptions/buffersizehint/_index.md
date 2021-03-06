---
title: BufferSizeHint
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или устанавливает подсказку о размере буфера которая определяет максимально допустимый размер для всех внутренних буферов.
type: docs
weight: 20
url: /ru/net/aspose.imaging/loadoptions/buffersizehint/
---
## LoadOptions.BufferSizeHint property

Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов.

```csharp
public int BufferSizeHint { get; set; }
```

### Стоимость имущества

Подсказка о размере буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

### Примеры

В следующем примере показано, как установить память ограничение при загрузке образа CMX. Предел памяти — это максимально допустимый размер (в мегабайтах) для всех внутренних буферов.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

 // Установка ограничения памяти в 50 мегабайт для целевого загруженного изображения
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

В следующем примере показано, как установить ограничение памяти при загрузке изображения JPEG. Предел памяти — это максимально допустимый размер (в мегабайтах) для всех внутренних буферов.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

 // Установка ограничения памяти в 50 мегабайт для целевого загруженного изображения
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

### Смотрите также

* class [LoadOptions](../../loadoptions)
* пространство имен [Aspose.Imaging](../../loadoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
