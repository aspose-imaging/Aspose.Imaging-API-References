---
title: "IMatchingSession.Save"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة IMatchingSession. احفظ حالة الجلسة إلى الدفق المحدد"
type: docs
weight: 50
url: /ar/net/aspose.imaging.masking/imaskingsession/save/
---
## Save(Stream) {#save}

احفظ حالة الجلسة إلى الدفق المحدد.

```csharp
public void Save(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |

### انظر أيضًا

* interface [IMaskingSession](../)
* namespace [Aspose.Imaging.Masking](../../imaskingsession/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_1}

يحفظ حالة الجلسة إلى الملف المحدد.

```csharp
public void Save(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |

## أمثلة

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

* interface [IMaskingSession](../)
* namespace [Aspose.Imaging.Masking](../../imaskingsession/)
* assembly [Aspose.Imaging](../../../)


