---
title: AssumedObjectData
second_title: Справочник по Aspose.Imaging for .NET API
description: Данные предполагаемого объекта. Включает тип и площадь объекта.
type: docs
weight: 10440
url: /ru/aspose.imaging.masking.options/assumedobjectdata/
---
## AssumedObjectData class

Данные предполагаемого объекта. Включает тип и площадь объекта.

```csharp
public class AssumedObjectData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AssumedObjectData](assumedobjectdata#constructor)() | Инициализирует новый экземпляр[`AssumedObjectData`](../assumedobjectdata) класс. |
| [AssumedObjectData](assumedobjectdata#constructor_1)(DetectedObjectType, Rectangle) | Инициализирует новый экземпляр[`AssumedObjectData`](../assumedobjectdata) класс. |
| [AssumedObjectData](assumedobjectdata#constructor_2)(string, Rectangle) | Инициализирует новый экземпляр[`AssumedObjectData`](../assumedobjectdata) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.imaging.masking.options/assumedobjectdata/bounds) { get; set; } | Получает или устанавливает границы объекта. |
| [Type](../../aspose.imaging.masking.options/assumedobjectdata/type) { get; set; } | Получает или задает тип объекта. |

### Примеры

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

* пространство имен [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
