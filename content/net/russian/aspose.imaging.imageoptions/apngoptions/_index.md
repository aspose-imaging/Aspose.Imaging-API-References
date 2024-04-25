---
title: ApngOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Формат анимированного файла PNG options
type: docs
weight: 9900
url: /ru/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Формат анимированного файла PNG options

```csharp
public class ApngOptions : PngOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ApngOptions](apngoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | Битовая глубина. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Получает или задает тип цвета. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | Уровень сжатия изображения png в диапазоне от 0 до 9, где 9 — максимальное сжатие, а 0 — режим сохранения. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Получает или задает длительность кадра по умолчанию. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Получает или задает тип фильтра, используемый во время процесса сохранения файла png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Получает или задает количество циклов анимации. 0 указывает на бесконечный цикл. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Получает или задает значение, указывающее, является ли это[`PngOptions`](../pngoptions) является прогрессивным. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

В следующем примере показано, как экспортировать файл apng в формате APNG из другого неанимированного многостраничного формата.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Установка длительности кадра по умолчанию
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 мс
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 мс
}
```

В следующем примере показано, как выполнить экспорт в формат файла APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Экспорт в APNG-анимацию с неограниченным количеством циклов анимации по умолчанию
    image.Save("Animation1.webp.png", new ApngOptions());
    // Настройка циклов анимации
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 циклов
}
```

В следующем примере показано, как создать изображение APNG из другого растрового одностраничного изображения.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 с
const int FrameDuration = 70; // 70 мс
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Здесь можно установить время кадра изображения по умолчанию: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Очистка, так как изображение по умолчанию содержит один кадр
        apngImage.RemoveAllFrames();

        // добавляем первый кадр
        apngImage.AddFrame(sourceImage);

        // добавляем промежуточные кадры
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // добавляем последний кадр
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Смотрите также

* class [PngOptions](../pngoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
