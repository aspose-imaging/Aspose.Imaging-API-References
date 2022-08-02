---
title: Compression
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает сжатие.
type: docs
weight: 90
url: /ru/net/aspose.imaging.imageoptions/tiffoptions/compression/
---
## TiffOptions.Compression property

Получает или задает сжатие.

```csharp
public TiffCompressions Compression { get; set; }
```

### Стоимость имущества

Сжатие.

### Примеры

В этом примере показано, как создать изображение TIFF с нуля и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Устанавливаем 8 бит для каждого компонента цвета.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Установить порядок байтов с обратным порядком байтов (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Установить сжатие LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Установить цветовую модель RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Все компоненты цвета будут храниться в одной плоскости.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Создаем кадр TIFF размером 100x100 пикселей.
// Обратите внимание, что вам не нужно явно удалять фрейм, если он включен в TiffImage.
// При удалении контейнера все фреймы будут удалены автоматически.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Заливаем всю рамку сине-желтым градиентом.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

В этом примере показано, как сохранить растровое изображение в формате TIFF, используя различные параметры.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Устанавливаем 8 бит для каждого компонента цвета.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Установить порядок байтов с обратным порядком байтов (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Установить сжатие LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Разрешить уменьшать размер изображений с непрерывным тонированием.
// В настоящее время это поле используется только с кодировкой LZW, потому что LZW, вероятно, является единственной схемой кодирования TIFF
// что значительно выигрывает от шага предиктора.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Установить цветовую модель RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Для YCbCr вы можете использовать один из следующих вариантов:
// Поле YCbCrSubSampling Коэффициенты выборки JPEG
// -------------------------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2 (значение по умолчанию) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Все компоненты цвета будут храниться в одной плоскости.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Создаем кадр TIFF размером 100x100 пикселей.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Заливаем все изображение сине-желтым градиентом.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

В этом примере показано, как создать изображение TIFF с двумя кадрами и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

// Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Устанавливаем 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Установить порядок байтов с обратным порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Создаем первый кадр TIFF размером 100x100 пикселей.
// Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
// При удалении контейнера все фреймы будут удалены автоматически.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Заливаем первый кадр сине-желтым градиентом.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установите 1 бит на пиксель для черно-белого изображения.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Установить порядок байтов с прямым порядком байтов (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Заливаем второй кадр сине-желтым градиентом.
// Он будет автоматически конвертирован в Ч/Б формат за счет соответствующих настроек кадра.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Смотрите также

* enum [TiffCompressions](../../../aspose.imaging.fileformats.tiff.enums/tiffcompressions)
* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
