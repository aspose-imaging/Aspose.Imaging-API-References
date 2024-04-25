---
title: WebPImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярWebPImageaspose.imaging.fileformats.webp/webpimage class из потока.
type: docs
weight: 10
url: /ru/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) class из потока.

```csharp
public WebPImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Потоковое изображение WebP. |

### Примеры

В этом примере показано, как загрузить изображение WebP из файлового потока и сохранить его в формате PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение WebP из файлового потока.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Сохранить в PNG
    // Обратите внимание, что в формате PNG будет сохранен только активный кадр, так как PNG не является многостраничным форматом.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс из потока.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Потоковое изображение WebP. |
| loadOptions | LoadOptions | Варианты загрузки. |

### Смотрите также

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс из файла .

```csharp
public WebPImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к файлу изображения WebP |

### Примеры

В этом примере показано, как загрузить изображение WebP из файла и сохранить его в формате PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение WebP из файла.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Сохранить в PNG
    // Обратите внимание, что в формате PNG будет сохранен только активный кадр, так как PNG не является многостраничным форматом.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс из файла .

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к файлу изображения WebP |
| loadOptions | LoadOptions | Варианты загрузки. |

### Смотрите также

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс из rasterImage.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Растровое изображение. |

### Примеры

В этом примере показано, как создать изображение WebP из другого растрового изображения.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузите изображение PNG размером 100x100 пикселей.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Создаем изображение WebP на основе изображения PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Сохранить в файл WebP с параметрами по умолчанию
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс из rasterImage.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Растровое изображение. |
| loadOptions | LoadOptions | Варианты загрузки. |

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс с пустым изображением.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения |
| height | Int32 | Высота изображения. |
| options | WebPOptions | Варианты. |

### Примеры

В этом примере показано, как создать изображение WebP с указанными параметрами с нуля.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Создаем изображение WebP размером 100x100 пикселей.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Заливаем все изображение красным.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Сохраняем в файл WebP
    webPImage.Save(dir + "output.webp");
}
```

В этом примере показано, как создать многокадровое анимированное изображение WebP с указанными параметрами.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Кадр по умолчанию плюс 36 + 36 дополнительных кадров.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Создаем изображение WebP размером 100x100 пикселей.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Первый круг красный
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Второй круг черный
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Постепенно увеличивайте угол красной дуги.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Постепенно увеличивайте угол черной дуги и стирайте красную дугу.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Сохраняем в файл WebP
    webPImage.Save(dir + "output.webp");
}
```

### Смотрите также

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Инициализирует новый экземпляр[`WebPImage`](../../webpimage) класс с пустым изображением.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения |
| height | Int32 | Высота изображения. |
| options | WebPOptions | Варианты. |
| loadOptions | LoadOptions | Варианты загрузки. |

### Смотрите также

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
