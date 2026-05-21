---
title: "الفئة AutoMaskingGraphCutOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Masking.Options.AutoMaskingGraphCutOptions. خيارات القناع التلقائي GraphCut"
type: docs
weight: 11010
url: /ar/net/aspose.imaging.masking.options/automaskinggraphcutoptions/
---
## AutoMaskingGraphCutOptions class

خيارات الإخفاء التلقائي GraphCut.

```csharp
public class AutoMaskingGraphCutOptions : GraphCutMaskingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AutoMaskingGraphCutOptions](automaskinggraphcutoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Args](../../aspose.imaging.masking.options/maskingoptions/args/) { get; set; } | يحصل أو يضبط الوسائط لخوارزمية التجزئة. |
| [AssumedObjects](../../aspose.imaging.masking.options/automaskinggraphcutoptions/assumedobjects/) { get; set; } | يحصل أو يضبط الكائنات المفترضة. |
| [BackgroundReplacementColor](../../aspose.imaging.masking.options/maskingoptions/backgroundreplacementcolor/) { get; set; } | يحصل أو يضبط لون استبدال الخلفية. |
| [CalculateDefaultStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/calculatedefaultstrokes/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب حساب الضربات الافتراضية. |
| [Decompose](../../aspose.imaging.masking.options/maskingoptions/decompose/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان من غير الضروري فصل كل شكل عن القناع ككائن فردي أو ككائن موحد من القناع مفصول عن الخلفية. |
| [DefaultBackgroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes/) { get; } | يحصل على الضربات الخلفية الافتراضية. |
| [DefaultForegroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultforegroundstrokes/) { get; } | يحصل على الضربات الأمامية الافتراضية المحسوبة مسبقًا. |
| [DefaultObjectsRectangles](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles/) { get; } | يحصل على مستطيلات الكائنات الافتراضية. |
| [ExportOptions](../../aspose.imaging.masking.options/maskingoptions/exportoptions/) { get; set; } | يحصل أو يضبط خيارات تصدير الصورة. |
| [FeatheringRadius](../../aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius/) { get; set; } | يحصل أو يضبط نصف قطر التدرج. |
| [MaskingArea](../../aspose.imaging.masking.options/maskingoptions/maskingarea/) { get; set; } | يحصل أو يضبط منطقة القناع. |
| [Method](../../aspose.imaging.masking.options/maskingoptions/method/) { get; set; } | يحصل أو يضبط طريقة التجزئة. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.masking.options/automaskinggraphcutoptions/precalculationprogresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث تقدم عملية ما قبل حساب النقاط الافتراضية. |

## أمثلة

حفظ نتيجة قناع الصورة مع التدرج بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. يمكن حذف خاصية Args في AutoMaskingGraphCutOptions لأن الضربات الافتراضية توضع هناك في النهاية.

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

حفظ نتيجة قناع الصورة مع التدرج بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects في AutoMaskingGraphCutOptions.

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

حفظ نتيجة قناع الصورة مع التدرج بناءً على حجم الصورة وإعادة استخدام خيارات القناع للتكرار الجديد للقناع. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects في AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر.

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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية 
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // إعادة استخدام AutoMaskingGraphCutOptions لا يلزم إجراء حسابات الضربات الافتراضية مرة ثانية.
    options.CalculateDefaultStrokes = false;
    // عند توفير كل من الضربات الافتراضية وObjectsPoints في خاصية Args الخاصة بـ AutoMaskingArgs، يتم دمج مصفوفات Point.
    // يُعتبر مصفوفة ObjectsPoints الأولى مصفوفة نقاط خلفية و
    // المصفوفة الثانية من ObjectsPoints تُعتبر مصفوفة نقاط أمامية.
    // عند توفير كل من DefaultObjectsRectangles وObjectsRectangles في خاصية Args الخاصة بـ AutoMaskingArgs،
    // يتم استخدام المصفوفة فقط من Args.
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

حفظ نتيجة قناع الصورة مع تمويه يعتمد على حجم الصورة، تعديل الضربات الافتراضية المستحصلة واستخدامها في تكرار القناع الجديد. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects الخاصة بـ AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل ضربات الخلفية/الأمام المطبقة ويتم إجراء تكرار قناع آخر باستخدام نسخة جديدة من GraphCutMaskingOptions.

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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية 
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.
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

### انظر أيضًا

* class [GraphCutMaskingOptions](../graphcutmaskingoptions/)
* namespace [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options/)
* assembly [Aspose.Imaging](../../)


