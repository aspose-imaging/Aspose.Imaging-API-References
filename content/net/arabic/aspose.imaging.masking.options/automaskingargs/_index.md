---
title: AutoMaskingArgs
second_title: Aspose.Imaging لمرجع NET API
description: يمثل الوسيطات المحددة لطرق التقنيع الآلية
type: docs
weight: 10450
url: /ar/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

يمثل الوسيطات المحددة لطرق التقنيع الآلية

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AutoMaskingArgs](automaskingargs)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber) { get; set; } | الحصول على أو تعيين الحد الأقصى لعدد التكرارات . |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects) { get; set; } | الحصول على أو تعيين عدد الكائنات لفصل الصورة الأولية إلى (اختياري) ، القيمة الافتراضية هي 2 (الكائن والخلفية) . |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints) { get; set; } | الحصول على أو تعيين النقاط التي تنتمي إلى الكائنات المنفصلة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects للصورة الأولية . يتم استخدام هذه المعلمة لزيادة دقة أسلوب التجزئة. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles) { get; set; } | الحصول على أو تعيين مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري) . يتم استخدام هذه المعلمة لزيادة دقة طريقة التجزئة. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints) { get; set; } | الحصول على أو تعيين النقاط التي لم تعد تنتمي إلى أي كائن (اختياري) . يتم استخدام هذه المعلمة فقط في حالة إعادة التقسيم . |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision) { get; set; } | الحصول على أو تعيين دقة طريقة التجزئة (اختياري) . |

### أمثلة

يوضح هذا المثال كيفية تحليل صورة نقطية إلى صور متعددة باستخدام إخفاء الصورة وخوارزمية التجزئة K-mean. إخفاء الصورة عبارة عن تقنية لمعالجة الصور تُستخدم لفصل الخلفية عن كائنات الصورة الأمامية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // تعيين عدد المجموعات (كائنات منفصلة). القيمة الافتراضية هي 2 ، الكائن الأمامي والخلفية.
    args.NumberOfObjects = 3;

    // تعيين الحد الأقصى لعدد التكرارات.
    args.MaxIterationNumber = 50;

    // ضبط دقة طريقة التجزئة (اختياري)
    args.Precision = 1;
        
    // سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // استخدم K- الوسائل العنقودية.
    // K-mean clustering يسمح بتقسيم الصورة إلى عدة مجموعات (شرائح) مستقلة.
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // سيكون لون backgroung برتقالي.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (شرائح).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على صور من نتيجة التقنيع وحفظها في PNG.
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

استخدام قناع مقطعي لتسريع عملية التجزئة

```csharp
[C#]

// إخفاء خيارات التصدير
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// سيكون لون backgroung شفافًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // تصغير حجم الصورة لتسريع عملية التجزئة
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (شرائح).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على القناع الأمامي
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // قم بزيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على مقطع أمامي
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

يوضح هذا المثال كيفية تحديد اقتراحات لخوارزمية إخفاء الصورة لتحسين دقة طريقة التجزئة (التجميع). إخفاء الصورة عبارة عن تقنية لمعالجة الصور تُستخدم لفصل الخلفية عن كائنات الصورة الأمامية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // الاقتراح رقم 1.
    // تحليل الصورة بصريًا وتعيين منطقة الاهتمام. ستشمل نتيجة التجزئة فقط الكائنات التي سيتم تحديد موقعها بالكامل داخل هذه المنطقة.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // الاقتراح رقم 2.
    // تحليل الصورة بصريًا وتعيين النقاط التي تنتمي إلى كائنات منفصلة.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // استخدم تجميع GraphCut.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // سيكون لون backgroung برتقالي.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (شرائح).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على صور من نتيجة التقنيع وحفظها في PNG.
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

حفظ جلسة التقنيع في ملف لجلسات طويلة وكذلك لإمكانية استئناف الجلسة في بيئة أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// إخفاء خيارات التصدير
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// سيكون لون backgroung برتقالي.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// بدء جلسة لأول مرة وحفظها في ملف
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // إنشاء مثيل لفئة ImageMasking.
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

// استئناف جلسة اخفاء من ملف
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // تحليل الصورة بصريًا وتعيين النقاط التي تنتمي إلى كائنات منفصلة.
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
            // النقل الصريح لخيارات التصدير ، نظرًا لأنه غير قابل للتسلسل
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### أنظر أيضا

* interface [IMaskingArgs](../imaskingargs)
* مساحة الاسم [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
