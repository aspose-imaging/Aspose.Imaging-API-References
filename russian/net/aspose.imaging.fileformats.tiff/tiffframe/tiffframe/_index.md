---
title: TiffFrame
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаTiffFrameaspose.imaging.fileformats.tiff/tiffframe.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации пикселя кадра и данных палитры. |

### Смотрите также

* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| options | TiffOptions | Параметры для вновь созданного фрейма. |

### Смотрите также

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации пикселя кадра и данных палитры. |

### Смотрите также

* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации пикселя кадра и данных палитры. |
| options | TiffOptions | Параметры для вновь созданного фрейма. |

### Смотрите также

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(RasterImage image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение для инициализации пикселей кадра и данных палитры. |

### Примеры

В следующем примере показано, как составить многостраничный TIFF из отдельных растровых изображений.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
     // Это шрифт и кисть для рисования текста на отдельных кадрах.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

     // Создаем 5 кадров
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Создаем изображение в формате PNG и рисуем на нем номер страницы.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

         // Создаем рамку на основе изображения PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

         // Добавляем кадр к изображению TIFF.
        tiffImage.AddFrame(frame);
    }

     // Изображение было создано с одним кадром по умолчанию. Давайте удалим его.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

     // Не забудьте удалить кадр, если вы не собираетесь добавлять его в какой-то другой TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение для инициализации пикселей кадра и данных палитры. |
| options | TiffOptions | Параметры для вновь созданного фрейма. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Инициализирует новый экземпляр класса[`TiffFrame`](../../tiffframe).

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | TiffOptions | Параметры кадра. |
| width | Int32 | Ширина. |
| height | Int32 | Высота. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Параметр Options имеет значение null. |

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

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
