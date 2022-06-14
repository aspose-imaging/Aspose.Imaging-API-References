---
title: TiffOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаTiffOptionsaspose.imaging.imageoptions/tiffoptions.
type: docs
weight: 10
url: /ru/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Инициализирует новый экземпляр класса[`TiffOptions`](../../tiffoptions).

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Ожидаемый формат файла tiff. |
| byteOrder | TiffByteOrder | Используемый порядок байтов в формате файла tiff. |

### Смотрите также

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Инициализирует новый экземпляр класса[`TiffOptions`](../../tiffoptions). По умолчанию используется соглашение с прямым порядком байтов.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Ожидаемый формат файла tiff. |

### Примеры

В следующем примере показано, как создать копию существующего кадра в градациях серого и добавить ее к изображению TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Разрешить уменьшать размер изображений с непрерывными тонами.
 // В настоящее время это поле используется только с кодировкой LZW, поскольку LZW, вероятно, является единственной схемой кодирования TIFF
 // что значительно выигрывает от шага предиктора.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

 // Установить цветовую модель RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Для YCbCr вы можете использовать один из следующих вариантов: 
 // Поле YCbCrSubSampling Факторы выборки JPEG
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

В этом примере показано, как сохранить растровое изображение в формате TIFF с использованием различных опций.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Установить 8 бит для каждого компонента цвета.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

 // Установить порядок байтов с прямым порядком байтов (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

 // Установить сжатие LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

 // Разрешить уменьшать размер изображений с непрерывными тонами.
 // В настоящее время это поле используется только с кодировкой LZW, поскольку LZW, вероятно, является единственной схемой кодирования TIFF
 // что значительно выигрывает от шага предиктора.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

 // Установить цветовую модель RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

 // Для YCbCr вы можете использовать один из следующих вариантов: 
 // Поле YCbCrSubSampling Факторы выборки JPEG
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

### Смотрите также

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Инициализирует новый экземпляр класса[`TiffOptions`](../../tiffoptions).

```csharp
public TiffOptions(TiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | TiffOptions | Опции для копирования. |

### Смотрите также

* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Инициализирует новый экземпляр класса[`TiffOptions`](../../tiffoptions).

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | TiffDataType[] | Теги для инициализации опций. |

### Смотрите также

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../tiffoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
