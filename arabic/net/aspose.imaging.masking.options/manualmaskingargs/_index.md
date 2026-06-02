---
title: "الفئة ManualMaskingArgs"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Masking.Options.ManualMaskingArgs. تمثل الوسائط التي يتم تحديدها لطريقة القناع اليدوي"
type: docs
weight: 11050
url: /ar/net/aspose.imaging.masking.options/manualmaskingargs/
---
## ManualMaskingArgs class

يمثل المعلمات المحددة لطريقة القناع اليدوي

```csharp
public class ManualMaskingArgs : IMaskingArgs
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ManualMaskingArgs](manualmaskingargs/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Mask](../../aspose.imaging.masking.options/manualmaskingargs/mask/) { get; set; } | يحصل أو يضبط مجموعة الأشكال الرسومية التي تشكل القناع. |

## أمثلة

يوضح هذا المثال كيفية تفكيك صورة نقطية إلى صور متعددة باستخدام قناع الصورة وقناع يدوي. قناع الصورة هو تقنية معالجة صور تُستخدم لتقسيم الخلفية عن كائنات الصورة في المقدمة.

```csharp
[C#]

string dir = "c:\\temp\\";

// عرّف قناعًا يدويًا.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// سيتم حفظ كل مجموعة (مقطع) في ملف PNG منفصل.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// حدد القناع اليدوي.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // استخدم خوارزمية التجميع اليدوي.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // سيتم دمج جميع الأشكال التي تشكل القناع في واحدة.
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // المنطقة في الصورة المصدر التي سيُطبق عليها القناع.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

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

* interface [IMaskingArgs](../imaskingargs/)
* namespace [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options/)
* assembly [Aspose.Imaging](../../)


