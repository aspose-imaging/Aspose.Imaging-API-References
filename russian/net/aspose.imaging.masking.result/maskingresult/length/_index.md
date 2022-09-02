---
title: Length
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает длину.
type: docs
weight: 30
url: /ru/net/aspose.imaging.masking.result/maskingresult/length/
---
## MaskingResult.Length property

Получает длину.

```csharp
public int Length { get; }
```

### Стоимость имущества

Длина.

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

В этом примере показано, как разложить растровое изображение на несколько изображений с помощью маскирования изображения и ручной маски. Маскирование изображения — это метод обработки изображения, который используется для отделения фона от объектов изображения переднего плана.

```csharp
[C#]

string dir = "c:\\temp\\";

// Определяем ручную маску.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Каждый кластер (сегмент) будет храниться в отдельном файле PNG.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Установить маску вручную.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Использовать ручной алгоритм кластеризации.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Все фигуры, составляющие маску, будут объединены в одну. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Цвет фона будет оранжевый.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Область исходного изображения, к которой будет применяться маскирование.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

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

### Смотрите также

* class [MaskingResult](../../maskingresult)
* пространство имен [Aspose.Imaging.Masking.Result](../../maskingresult)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
