---
title: AutoMaskingGraphCutOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات التقنيع التلقائي لـ GraphCut .
type: docs
weight: 10460
url: /ar/aspose.imaging.masking.options/automaskinggraphcutoptions/
---
## AutoMaskingGraphCutOptions class

خيارات التقنيع التلقائي لـ GraphCut .

```csharp
public class AutoMaskingGraphCutOptions : GraphCutMaskingOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AutoMaskingGraphCutOptions](automaskinggraphcutoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Args](../../aspose.imaging.masking.options/maskingoptions/args) { get; set; } | الحصول على أو تعيين وسيطات خوارزمية التجزئة. |
| [AssumedObjects](../../aspose.imaging.masking.options/automaskinggraphcutoptions/assumedobjects) { get; set; } | الحصول على الكائنات المفترضة أو تعيينها. |
| [BackgroundReplacementColor](../../aspose.imaging.masking.options/maskingoptions/backgroundreplacementcolor) { get; set; } | الحصول على أو تعيين لون استبدال الخلفية . |
| [CalculateDefaultStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/calculatedefaultstrokes) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب حساب الحدود الافتراضية. |
| [Decompose](../../aspose.imaging.masking.options/maskingoptions/decompose) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان غير ضروري لفصل كل شكل عن قناع ككائن فردي أو ككائن موحد من قناع منفصل عن الخلفية. |
| [DefaultBackgroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes) { get; } | يحصل على ضربات الخلفية الافتراضية. |
| [DefaultForegroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultforegroundstrokes) { get; } | يحصل على ضربات المقدمة الافتراضية المحسوبة مسبقًا. |
| [DefaultObjectsRectangles](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles) { get; } | يحصل على مستطيلات الكائنات الافتراضية. |
| [ExportOptions](../../aspose.imaging.masking.options/maskingoptions/exportoptions) { get; set; } | الحصول على أو تعيين خيارات تصدير الصورة. |
| [FeatheringRadius](../../aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius) { get; set; } | الحصول على أو تحديد نصف قطر الحد المتدرج. |
| [MaskingArea](../../aspose.imaging.masking.options/maskingoptions/maskingarea) { get; set; } | الحصول على منطقة التقنيع أو تعيينها . |
| [Method](../../aspose.imaging.masking.options/maskingoptions/method) { get; set; } | الحصول على أو تحديد طريقة التجزئة . |
| [PrecalculationProgressEventHandler](../../aspose.imaging.masking.options/automaskinggraphcutoptions/precalculationprogresseventhandler) { get; set; } | الحصول على أو تعيين معالج حدث تقدم عملية الحساب المسبق للنقاط. |

### أمثلة

حفظ نتيجة إخفاء الصورة باستخدام التدرج بناءً على حجم الصورة. يتم تنفيذ إخفاء الصورة باستخدام حدود افتراضية محسوبة تلقائيًا. يمكن حذف خاصية Args الخاصة بـ AutoMaskingGraphCutOptions حيث يتم وضع حدود الشكل الافتراضية هناك في النهاية.

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

حفظ نتيجة إخفاء الصورة باستخدام التدرج بناءً على حجم الصورة. يتم تنفيذ إخفاء الصورة باستخدام حدود افتراضية محسوبة تلقائيًا. بالإضافة إلى ذلك ، يتم أيضًا تحديد بيانات الكائنين المفترضين في خاصية AssumedObjects الخاصة بـ AutoMaskingGraphCutOptions.

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

حفظ نتيجة إخفاء الصورة باستخدام التدرج بناءً على حجم الصورة وإعادة استخدام خيارات التقنيع لتكرار التقنيع الجديد. يتم تنفيذ إخفاء الصورة باستخدام حدود افتراضية محسوبة تلقائيًا. بالإضافة إلى ذلك ، يتم أيضًا تحديد بيانات الكائنين المفترضين في خاصية AssumedObjects الخاصة بـ AutoMaskingGraphCutOptions. بعد الحصول على نتيجة التقنيع الأولية ، يتم تعديل حدود الخلفية / المقدمة المطبقة ويتم إجراء تكرار آخر للقناع.

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

// في هذه المرحلة ، يمكن تحليل ضربات المقدمة / الخلفية المطبقة وبناءً عليها بشكل إضافي 
يمكن توفير حدود // المقدمة / الخلفية يدويًا.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // إعادة استخدام AutoMaskingGraphCutOptions ليست هناك حاجة لإجراء حسابات السكتات الدماغية الافتراضية مرة ثانية.
    options.CalculateDefaultStrokes = false;
    // عندما يتم توفير كل من حدود الشكل ونقاط الكائنات الافتراضية في خاصية Args الخاصة بـ AutoMaskingArgs ، يتم في النهاية تجميع مصفوفات النقاط.
    // تعتبر أول مصفوفة ObjectsPoints مصفوفة نقاط الخلفية و 
    // تعتبر مجموعة ObjectsPoints الثانية مصفوفة نقاط مقدمة.
    // عندما يتم توفير كل من DefaultObjectsRectangles و ObjectsRectangles في خاصية Args الخاصة بـ AutoMaskingArgs ، 
    // يتم استخدام المصفوفة من Args فقط.
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

حفظ نتيجة إخفاء الصورة بالتدرج بناءً على حجم الصورة ، وتعديل الحدود الافتراضية التي تم الحصول عليها واستخدامها لتكرار التقنيع الجديد. يتم تنفيذ إخفاء الصورة باستخدام حدود افتراضية محسوبة تلقائيًا. بالإضافة إلى ذلك ، يتم أيضًا تحديد بيانات الكائنين المفترضين في خاصية AssumedObjects الخاصة بـ AutoMaskingGraphCutOptions. بعد الحصول على نتيجة التقنيع الأولية ، يتم تعديل حدود الخلفية / المقدمة المطبقة ويتم إجراء تكرار آخر للقناع باستخدام مثيل GraphCutMaskingOptions الجديد.

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

// في هذه المرحلة ، يمكن تحليل ضربات المقدمة / الخلفية المطبقة وبناءً عليها بشكل إضافي 
يمكن توفير حدود // المقدمة / الخلفية يدويًا.
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

### أنظر أيضا

* class [GraphCutMaskingOptions](../graphcutmaskingoptions)
* مساحة الاسم [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
