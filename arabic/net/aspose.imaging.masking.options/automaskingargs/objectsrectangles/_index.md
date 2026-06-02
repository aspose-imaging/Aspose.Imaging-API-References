---
title: "AutoMaskingArgs.ObjectsRectangles"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية AutoMaskingArgs. تحصل أو تعيين مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة"
type: docs
weight: 50
url: /ar/net/aspose.imaging.masking.options/automaskingargs/objectsrectangles/
---
## AutoMaskingArgs.ObjectsRectangles property

يحصل أو يعيّن مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

```csharp
public Rectangle[] ObjectsRectangles { get; set; }
```

### Property Value

مستطيلات الكائنات.

## أمثلة

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

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [AutoMaskingArgs](../)
* namespace [Aspose.Imaging.Masking.Options](../../automaskingargs/)
* assembly [Aspose.Imaging](../../../)


