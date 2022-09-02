---
title: AssumedObjectData
second_title: Aspose.Imaging لمرجع NET API
description: بيانات الكائن المفترض. يتضمن نوع الكائن ومساحته.
type: docs
weight: 10440
url: /ar/net/aspose.imaging.masking.options/assumedobjectdata/
---
## AssumedObjectData class

بيانات الكائن المفترض. يتضمن نوع الكائن ومساحته.

```csharp
public class AssumedObjectData
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AssumedObjectData](assumedobjectdata#constructor)() | يقوم بتهيئة مثيل جديد لملف[`AssumedObjectData`](../assumedobjectdata) فئة . |
| [AssumedObjectData](assumedobjectdata#constructor_1)(DetectedObjectType, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`AssumedObjectData`](../assumedobjectdata) فئة . |
| [AssumedObjectData](assumedobjectdata#constructor_2)(string, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`AssumedObjectData`](../assumedobjectdata) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bounds](../../aspose.imaging.masking.options/assumedobjectdata/bounds) { get; set; } | الحصول على أو تعيين حدود الكائن. |
| [Type](../../aspose.imaging.masking.options/assumedobjectdata/type) { get; set; } | الحصول على نوع الكائن أو تحديده. |

### أمثلة

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

* مساحة الاسم [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
