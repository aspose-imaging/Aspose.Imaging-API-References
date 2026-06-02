---
title: "AutoMaskingArgs.MaxIterationNumber"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية AutoMaskingArgs. تحصل أو تعيين الحد الأقصى لعدد التكرارات"
type: docs
weight: 20
url: /ar/net/aspose.imaging.masking.options/automaskingargs/maxiterationnumber/
---
## AutoMaskingArgs.MaxIterationNumber property

يحصل أو يعيّن الحد الأقصى لعدد التكرارات.

```csharp
public int MaxIterationNumber { get; set; }
```

### Property Value

الحد الأقصى الأقصى لعدد التكرارات.

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

### انظر أيضًا

* class [AutoMaskingArgs](../)
* namespace [Aspose.Imaging.Masking.Options](../../automaskingargs/)
* assembly [Aspose.Imaging](../../../)


