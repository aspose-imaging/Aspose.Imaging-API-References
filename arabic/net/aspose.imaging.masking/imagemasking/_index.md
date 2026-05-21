---
title: "الفئة ImageMasking"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Masking.ImageMasking. توفر عمليات إخفاء الصور"
type: docs
weight: 10980
url: /ar/net/aspose.imaging.masking/imagemasking/
---
## ImageMasking class

يوفر عمليات تمويه الصورة

```csharp
public class ImageMasking
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageMasking](imagemasking/)(RasterImage) | يُهيئ نسخة جديدة من الفئة `ImageMasking`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateSession](../../aspose.imaging.masking/imagemasking/createsession/)(MaskingOptions) | ينشئ جلسة الإخفاء التي يمكنها تنفيذ عمليات تفكيك إعادة التدريب. |
| [Decompose](../../aspose.imaging.masking/imagemasking/decompose/)(MaskingOptions) | ينفذ عملية التفكيك باستخدام خيارات الإخفاء المحددة |
| [DecomposeAsync](../../aspose.imaging.masking/imagemasking/decomposeasync/)(MaskingOptions) | ينشئ مهمة التفكيك غير المتزامنة باستخدام خيارات الإخفاء المحددة. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession/#loadsession)(Stream) | حمّل الجلسة من الدفق المحدد. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession/#loadsession_1)(string) | حمّل الجلسة من الملف المحدد. |
| static [ApplyMask](../../aspose.imaging.masking/imagemasking/applymask/)(RasterImage, RasterImage, MaskingOptions) | يطبق القناع على الصورة المصدر المحددة. |

## أمثلة

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

* namespace [Aspose.Imaging.Masking](../../aspose.imaging.masking/)
* assembly [Aspose.Imaging](../../)


