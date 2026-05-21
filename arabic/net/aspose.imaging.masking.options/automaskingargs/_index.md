---
title: "فئة AutoMaskingArgs"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Masking.Options.AutoMaskingArgs. تمثل الوسائط المحددة لطرق القناع الآلية"
type: docs
weight: 11000
url: /ar/net/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

يمثل الوسائط المحددة لطرق الإخفاء الآلية

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AutoMaskingArgs](automaskingargs/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد التكرارات. |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects/) { get; set; } | يحصل أو يعيّن عدد الكائنات التي سيتم فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية). |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints/) { get; set; } | يحصل أو يعيّن النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles/) { get; set; } | يحصل أو يعيّن مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints/) { get; set; } | يحصل أو يعيّن النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). يُستخدم هذا المعامل فقط في حالة إعادة التجزئة. |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision/) { get; set; } | يحصل أو يعيّن دقة طريقة التجزئة (اختياري). |

## أمثلة

يوضح هذا المثال كيفية تفكيك صورة نقطية إلى صور متعددة باستخدام قناع الصورة وخوارزمية تجزئة K-means. قناع الصورة هو تقنية معالجة صور تُستخدم لتقسيم الخلفية عن كائنات الصورة في المقدمة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // حدد عدد المجموعات (الكائنات المفصولة). القيمة الافتراضية هي 2، كائن المقدمة والخلفية.
    args.NumberOfObjects = 3;

    // حدد الحد الأقصى لعدد التكرارات.
    args.MaxIterationNumber = 50;

    // حدد دقة طريقة التجزئة (اختياري)
    args.Precision = 1;
        
    // سيتم حفظ كل مجموعة (مقطع) في ملف PNG منفصل.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // استخدم تجميع K-means.
    // يتيح تجميع K-means تقسيم الصورة إلى عدة مجموعات مستقلة (مقاطع).
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // إنشاء نسخة من الفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // احصل على الصور من نتيجة القناع واحفظها بصيغة PNG.
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

استخدام قناع الجزء لتسريع عملية التجزئة

```csharp
[C#]

// خيارات تصدير القناع
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// لون الخلفية سيكون شفافًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // تقليل حجم الصورة لتسريع عملية التجزئة
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // إنشاء نسخة من الفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على قناع المقدمة
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // زيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على جزء من المقدمة
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

يوضح هذا المثال كيفية تحديد الاقتراحات لخوارزمية قناع الصورة لتحسين دقة طريقة التجزئة (التجميع). قناع الصورة هو تقنية معالجة صور تُستخدم لفصل الخلفية عن كائنات الصورة في المقدمة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // الاقتراح #1.
    // قم بتحليل الصورة بصريًا وحدد منطقة الاهتمام. سيتضمن نتيجة التجزئة فقط الكائنات التي تقع بالكامل داخل هذه المنطقة.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // الاقتراح #2.
    // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // سيتم حفظ كل مجموعة (مقطع) في ملف PNG منفصل.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // استخدم تجميع GraphCut.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // إنشاء نسخة من الفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // احصل على الصور من نتيجة القناع واحفظها بصيغة PNG.
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

حفظ جلسة القناع إلى ملف للجلسات الطويلة، وكذلك لإمكانية استئناف الجلسة في بيئة أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// خيارات تصدير القناع
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// لون الخلفية سيكون برتقاليًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// بدء جلسة للمرة الأولى وحفظها إلى ملف
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // إنشاء نسخة من الفئة ImageMasking.
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

// استئناف جلسة القناع من ملف
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // إنشاء نسخة من الفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
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
            // نقل صريح لخيارات التصدير، لأنها غير قابلة للتسلسل
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### انظر أيضًا

* interface [IMaskingArgs](../imaskingargs/)
* namespace [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options/)
* assembly [Aspose.Imaging](../../)


