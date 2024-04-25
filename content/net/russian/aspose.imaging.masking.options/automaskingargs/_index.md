---
title: AutoMaskingArgs
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет аргументы указанные для автоматических методов маскирования
type: docs
weight: 10450
url: /ru/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

Представляет аргументы, указанные для автоматических методов маскирования

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AutoMaskingArgs](automaskingargs)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber) { get; set; } | Получает или задает максимальное количество итераций. |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects) { get; set; } | Получает или задает количество объектов для разделения начального изображения на (необязательно), значение по умолчанию — 2 (объект и фон). |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints) { get; set; } | Получает или задает точки, принадлежащие разделенным объектам (необязательно) Координаты NumberOfObjects, принадлежащие объектам NumberOfObjects исходного изображения. Этот параметр используется для повышения точности метода сегментации. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles) { get; set; } | Получает или задает прямоугольники объектов, которые принадлежат разделенным объектам (необязательно). Этот параметр используется для повышения точности метода сегментации. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints) { get; set; } | Получает или задает точки, которые больше не принадлежат ни одному объекту (необязательно). Этот параметр используется только в случае пересегментации. |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision) { get; set; } | Получает или задает точность метода сегментации (необязательно). |

### Примеры

В этом примере показано, как разложить растровое изображение на несколько изображений с помощью маскирования изображения и алгоритма сегментации K-средних. Маскирование изображения — это метод обработки изображения, который используется для отделения фона от объектов изображения переднего плана.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Установить количество кластеров (отдельных объектов). Значение по умолчанию — 2, объект переднего плана и фон.
    args.NumberOfObjects = 3;

    // Установить максимальное количество итераций.
    args.MaxIterationNumber = 50;

    // Установить точность метода сегментации (необязательно)
    args.Precision = 1;
        
    // Каждый кластер (сегмент) будет храниться в отдельном файле PNG.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Использовать кластеризацию K-средних.
    // Кластеризация K-средних позволяет разбить изображение на несколько независимых кластеров (сегментов).
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // Цвет фона будет оранжевый.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Разделить исходное изображение на несколько кластеров (сегментов).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Получаем изображения из результата маскирования и сохраняем их в PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Использование маски сегмента для ускорения процесса сегментации

```csharp
[C#]

// Маскировка опций экспорта
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Использовать кластеризацию GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Цвет фона будет прозрачным.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Уменьшение размера изображения для ускорения процесса сегментации
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Разделить исходное изображение на несколько кластеров (сегментов).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Получение маски переднего плана
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Увеличиваем размер маски до размера исходного изображения
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Применение маски к исходному изображению для получения сегмента переднего плана
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

В этом примере показано, как указать предложения для алгоритма маскирования изображения, чтобы повысить точность метода сегментации (кластеризации). Маскирование изображения — это метод обработки изображения, который используется для отделения фона от объектов изображения переднего плана.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Предложение №1.
    // Визуально проанализируйте изображение и установите область интереса. Результат сегментации будет включать только те объекты, которые будут полностью расположены в пределах этой области.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Предложение №2.
    // Визуально проанализируйте изображение и установите точки, которые принадлежат разделенным объектам.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Каждый кластер (сегмент) будет храниться в отдельном файле PNG.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // Использовать кластеризацию GraphCut.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Цвет фона будет оранжевый.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Разделить исходное изображение на несколько кластеров (сегментов).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Получаем изображения из результата маскирования и сохраняем их в PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Сохранение сеанса маскирования в файл для длительных сеансов, а также для возможности возобновления сеанса в другом окружении.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Маскировка опций экспорта
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Использовать кластеризацию GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Цвет фона будет оранжевый.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Первый запуск сеанса и сохранение в файл
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Возобновление сеанса маскирования из файла
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Визуально проанализируйте изображение и установите точки, которые принадлежат разделенным объектам.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Явная передача параметров экспорта, так как это не сериализуемо
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Смотрите также

* interface [IMaskingArgs](../imaskingargs)
* пространство имен [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
