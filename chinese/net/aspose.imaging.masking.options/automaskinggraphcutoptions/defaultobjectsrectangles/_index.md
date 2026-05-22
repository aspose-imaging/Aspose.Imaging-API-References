---
title: "AutoMaskingGraphCutOptions.DefaultObjectsRectangles"
second_title: "Aspose.Imaging for .NET API 参考"
description: "AutoMaskingGraphCutOptions 属性。获取默认对象矩形"
type: docs
weight: 60
url: /zh/net/aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles/
---
## AutoMaskingGraphCutOptions.DefaultObjectsRectangles property

获取默认对象矩形。

```csharp
public Rectangle[] DefaultObjectsRectangles { get; }
```

## 示例

根据图像尺寸进行羽化后保存图像掩模结果，并在新的掩模迭代中重复使用掩模选项。图像掩模使用自动计算的默认笔画执行。此外，两个假定对象的数据也在 AutoMaskingGraphCutOptions 的 AssumedObjects 属性中指定。获取初始掩模结果后，已应用的背景/前景笔画被修改，并进行另一次掩模迭代。

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

// 此时可以分析已应用的前景/背景笔画，并基于此额外 
// 前景/背景笔画可以手动提供。
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // 重新使用 AutoMaskingGraphCutOptions 时，无需第二次执行默认笔画计算。
    options.CalculateDefaultStrokes = false;
    // 当在 AutoMaskingArgs 的 Args 属性中同时提供 default strokes 和 ObjectsPoints 时，Point 数组最终会合并。
    // 第一个 ObjectsPoints 数组被视为背景点数组，且 
    // 第二个 ObjectsPoints 数组被视为前景点数组。
    // 当在 AutoMaskingArgs 的 Args 属性中同时提供 DefaultObjectsRectangles 和 ObjectsRectangles 时，
    // 仅使用来自 Args 的数组。
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

根据图像大小进行羽化后保存图像遮罩结果，修改获得的 default strokes 并将其用于新的遮罩迭代。图像遮罩使用自动计算的 default strokes 执行。此外，两个假定对象的数据也在 AutoMaskingGraphCutOptions 的 AssumedObjects 属性中指定。获取初始遮罩结果后，已应用的背景/前景 strokes 被修改，并使用新的 GraphCutMaskingOptions 实例执行另一次遮罩迭代。

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

// 此时可以分析已应用的前景/背景笔画，并基于此额外 
// 前景/背景笔画可以手动提供。
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

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [AutoMaskingGraphCutOptions](../)
* namespace [Aspose.Imaging.Masking.Options](../../automaskinggraphcutoptions/)
* assembly [Aspose.Imaging](../../../)


