---
title: AutoMaskingGraphCutOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры автоматического маскирования GraphCut.
type: docs
weight: 10460
url: /ru/aspose.imaging.masking.options/automaskinggraphcutoptions/
---
## AutoMaskingGraphCutOptions class

Параметры автоматического маскирования GraphCut.

```csharp
public class AutoMaskingGraphCutOptions : GraphCutMaskingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AutoMaskingGraphCutOptions](automaskinggraphcutoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Args](../../aspose.imaging.masking.options/maskingoptions/args) { get; set; } | Получает или задает аргументы для алгоритма сегментации. |
| [AssumedObjects](../../aspose.imaging.masking.options/automaskinggraphcutoptions/assumedobjects) { get; set; } | Получает или задает предполагаемые объекты. |
| [BackgroundReplacementColor](../../aspose.imaging.masking.options/maskingoptions/backgroundreplacementcolor) { get; set; } | Получает или задает цвет замены фона. |
| [CalculateDefaultStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/calculatedefaultstrokes) { get; set; } | Получает или задает значение, указывающее, следует ли рассчитывать штрихи по умолчанию. |
| [Decompose](../../aspose.imaging.masking.options/maskingoptions/decompose) { get; set; } | Получает или задает значение, указывающее, нужно ли отделять каждую форму от маски как отдельный объект или как объединенный объект от маски, отделенной от фона. |
| [DefaultBackgroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes) { get; } | Получает фоновые штрихи по умолчанию. |
| [DefaultForegroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultforegroundstrokes) { get; } | Получает предварительно рассчитанные по умолчанию штрихи переднего плана. |
| [DefaultObjectsRectangles](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles) { get; } | Получает прямоугольники объектов по умолчанию. |
| [ExportOptions](../../aspose.imaging.masking.options/maskingoptions/exportoptions) { get; set; } | Получает или задает параметры экспорта изображения. |
| [FeatheringRadius](../../aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius) { get; set; } | Получает или задает радиус размытия. |
| [MaskingArea](../../aspose.imaging.masking.options/maskingoptions/maskingarea) { get; set; } | Получает или задает область маскирования. |
| [Method](../../aspose.imaging.masking.options/maskingoptions/method) { get; set; } | Получает или задает метод сегментации. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.masking.options/automaskinggraphcutoptions/precalculationprogresseventhandler) { get; set; } | Получает или задает обработчик события прогресса процесса предварительного расчета баллов по умолчанию. |

### Примеры

Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения. Маскирование изображения выполняется с помощью автоматически рассчитанных штрихов по умолчанию. Свойство Args AutoMaskingGraphCutOptions можно опустить, так как штрихи по умолчанию помещаются туда в конце.

```csharp
[C#]

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения. Маскирование изображения выполняется с помощью автоматически рассчитанных штрихов по умолчанию. Кроме того, данные двух предполагаемых объектов также указываются в свойстве AssumedObjects AutoMaskingGraphCutOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    AssumedObjects = assumedObjects,
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения и повторное использование параметров маскирования для новой итерации маскирования. Маскирование изображения выполняется с помощью автоматически рассчитанных штрихов по умолчанию. Кроме того, данные двух предполагаемых объектов также указываются в свойстве AssumedObjects AutoMaskingGraphCutOptions. После получения исходного результата маскирования применяемые штрихи фона/переднего плана изменяются и выполняется еще одна итерация маскирования.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// В этот момент можно проанализировать примененные штрихи переднего плана/фона и на их основе добавить 
// штрихи переднего плана/фона могут быть предоставлены вручную.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // При повторном использовании AutoMaskingGraphCutOptions нет необходимости выполнять расчет штрихов по умолчанию во второй раз.
    options.CalculateDefaultStrokes = false;
    // Когда в свойстве Args AutoMaskingArgs указаны как штрихи по умолчанию, так и ObjectsPoints, массивы Point объединяются.
    // Первый массив ObjectsPoints считается массивом фоновых точек и 
    // второй массив ObjectsPoints считается массивом точек переднего плана.
    // Когда в свойстве Args для AutoMaskingArgs указаны как DefaultObjectsRectangles, так и ObjectsRectangles, 
    // используется только массив из Args.
    options.Args = new AutoMaskingArgs()
                        {
                            ObjectsPoints = new Point[][]
                                                {
                                                    new Point[] { new Point(100, 100), new Point(150, 100) }, 
                                                    new Point[] { new Point(500, 200) }, 
                                                },
                            ObjectsRectangles = new Rectangle[]
                                                    {
                                                        new Rectangle(100, 100, 300, 300), 
                                                    }
                        };
    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения, изменение полученных по умолчанию штрихов и использование их для новой итерации маскирования. Маскирование изображения выполняется с помощью автоматически рассчитанных штрихов по умолчанию. Кроме того, данные двух предполагаемых объектов также указываются в свойстве AssumedObjects AutoMaskingGraphCutOptions. После получения исходного результата маскирования применяемые штрихи фона/переднего плана изменяются, и выполняется еще одна итерация маскирования с использованием нового экземпляра GraphCutMaskingOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// В этот момент можно проанализировать примененные штрихи переднего плана/фона и на их основе добавить 
// штрихи переднего плана/фона могут быть предоставлены вручную.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions()
                                                    {
                                                        FeatheringRadius = 3,
                                                        Method = SegmentationMethod.GraphCut,
                                                        Decompose = false,
                                                        ExportOptions = new PngOptions()
                                                                            {
                                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                                Source = new FileCreateSource("tempFile")
                                                                            },
                                                        BackgroundReplacementColor = Color.Transparent,
                                                        Args = new AutoMaskingArgs()
                                                                {
                                                                    ObjectsPoints = new Point[][]
                                                                                        {
                                                                                            appliedBackgroundStrokes,
                                                                                            appliedForegroundStrokes
                                                                                        },
                                                                    ObjectsRectangles = appliedObjectRectangles
                                                                }
                                                    };
    results = new ImageMasking(image).Decompose(graphCutOptions);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Смотрите также

* class [GraphCutMaskingOptions](../graphcutmaskingoptions)
* пространство имен [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
