---
title: WebPOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры изображения WebP
type: docs
weight: 10280
url: /ru/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

Параметры изображения WebP

```csharp
public class WebPOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WebPOptions](webpoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor) { get; set; } | Получает или задает цвет фона анимации. |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount) { get; set; } | Получает или задает количество циклов анимации. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless) { get; set; } | Получает или задает значение, указывающее, является ли это[`WebPOptions`](../webpoptions) без потерь. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality) { get; set; } | Получает или устанавливает качество. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

В этом примере показано, как создать изображение WebP из другого растрового изображения с другим качеством сжатия.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загружаем GIF-анимацию
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // для сжатия без потерь увеличение параметра качества увеличивает качество сжатия и уменьшает размер файла
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // размер файла: 42 КБ

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // размер файла: 41 КБ

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // размер файла: 40 КБ


    // для сжатия с потерями увеличение значения Quality повышает качество изображения и увеличивает размер файла
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // размер файла: 24 КБ

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // размер файла: 36 КБ

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // размер файла: 51 КБ
}
```

В следующем примере показано, как преобразовать многостраничное векторное изображение в формат WEBP в общем виде без ссылки на конкретный тип изображения.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Экспортировать только первые две страницы. Эти страницы будут представлены в виде анимированных кадров в выходном WEBP.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
