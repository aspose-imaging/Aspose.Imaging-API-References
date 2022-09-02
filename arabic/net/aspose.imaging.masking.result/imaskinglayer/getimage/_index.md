---
title: GetImage
second_title: Aspose.Imaging لمرجع NET API
description: يقدم صورة النتيجة .
type: docs
weight: 20
url: /ar/net/aspose.imaging.masking.result/imaskinglayer/getimage/
---
## IMaskingLayer.GetImage method

يقدم صورة النتيجة .

```csharp
public RasterImage GetImage()
```

### قيمة الإرجاع

نتيجة الصورة.

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

يوضح هذا المثال كيفية تحليل صورة نقطية إلى صور متعددة باستخدام إخفاء الصورة والقناع اليدوي. إخفاء الصورة عبارة عن تقنية لمعالجة الصور تُستخدم لفصل الخلفية عن كائنات الصورة الأمامية.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحديد قناع يدوي.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// تعيين القناع اليدوي.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // استخدم خوارزمية التجميع اليدوي.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // سيتم دمج جميع الأشكال المكونة للقناع في شكل واحد. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // سيكون لون backgroung برتقالي.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // منطقة الصورة المصدر التي سيتم تطبيق التقنيع عليها.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

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

* class [RasterImage](../../../aspose.imaging/rasterimage)
* interface [IMaskingLayer](../../imaskinglayer)
* مساحة الاسم [Aspose.Imaging.Masking.Result](../../imaskinglayer)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
