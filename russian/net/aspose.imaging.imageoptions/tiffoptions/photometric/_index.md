---
title: Photometric
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает фотометрический параметр.
type: docs
weight: 340
url: /ru/net/aspose.imaging.imageoptions/tiffoptions/photometric/
---
## TiffOptions.Photometric property

Получает или задает фотометрический параметр.

```csharp
public TiffPhotometrics Photometric { get; set; }
```

### Стоимость имущества

Фотометрический.

### Примеры

В этом примере показано, как создать изображение TIFF с нуля и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

 // Создаем первый кадр TIFF размером 100x100 px.
 // Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
 // При удалении контейнера все кадры будут удалены автоматически.
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

 // Установить порядок байтов Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

 // Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

 // Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

 // Заливаем второй кадр сине-желтым градиентом.
 // Он будет автоматически конвертирован в Ч/Б формат из-за соответствующих настроек кадра.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

 // Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

В следующем примере показано, как составить многостраничный TIFF из отдельных растровых изображений.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

 // Создаем первый кадр TIFF размером 100x100 px.
 // Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
 // При удалении контейнера все кадры будут удалены автоматически.
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

 // Установить порядок байтов Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

 // Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

 // Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

 // Заливаем второй кадр сине-желтым градиентом.
 // Он будет автоматически конвертирован в Ч/Б формат из-за соответствующих настроек кадра.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

 // Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

В следующем примере показано, как создать копию существующего кадра в градациях серого и добавить ее к изображению TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

 // Создаем первый кадр TIFF размером 100x100 px.
 // Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
 // При удалении контейнера все кадры будут удалены автоматически.
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

 // Установить порядок байтов Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

 // Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

 // Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

 // Заливаем второй кадр сине-желтым градиентом.
 // Он будет автоматически конвертирован в Ч/Б формат из-за соответствующих настроек кадра.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

 // Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

В этом примере показано, как сохранить растровое изображение в формате TIFF с использованием различных опций.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

 // Создаем первый кадр TIFF размером 100x100 px.
 // Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
 // При удалении контейнера все кадры будут удалены автоматически.
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

 // Установить порядок байтов Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

 // Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

 // Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

 // Заливаем второй кадр сине-желтым градиентом.
 // Он будет автоматически конвертирован в Ч/Б формат из-за соответствующих настроек кадра.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

 // Создаем изображение в формате TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

В этом примере показано, как создать изображение TIFF с двумя кадрами и сохранить его в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Опции для первого кадра
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Установить цветовую модель RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Все компоненты цвета будут храниться в одной плоскости.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

 // Создаем первый кадр TIFF размером 100x100 px.
 // Обратите внимание, что вам не нужно явно удалять кадры, если они включены в TiffImage.
 // При удалении контейнера все кадры будут удалены автоматически.
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

 // Установить порядок байтов Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Установите сжатие факса CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

 // Установите цветовую модель Ч/Б, где 0 — черный, 1 — белый.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

 // Создаем второй кадр TIFF размером 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

 // Заливаем второй кадр сине-желтым градиентом.
 // Он будет автоматически конвертирован в Ч/Б формат из-за соответствующих настроек кадра.
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

* enum [TiffPhotometrics](../../../aspose.imaging.fileformats.tiff.enums/tiffphotometrics)
* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
