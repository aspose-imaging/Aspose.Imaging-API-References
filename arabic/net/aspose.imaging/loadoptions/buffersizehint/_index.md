---
title: "LoadOptions.BufferSizeHint"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية LoadOptions. يحصل أو يضبط تلميح حجم المخزن المؤقت الذي يُعرف كحد أقصى مسموح به لجميع المخازن الداخلية"
type: docs
weight: 20
url: /ar/net/aspose.imaging/loadoptions/buffersizehint/
---
## LoadOptions.BufferSizeHint property

الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية.

```csharp
public int BufferSizeHint { get; set; }
```

### Property Value

تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن الداخلية

## أمثلة

المثال التالي يوضح كيفية تعيين حد الذاكرة عند تحميل صورة CMX. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// تعيين حد الذاكرة إلى 10 ميغابايت للصورة المحملة المستهدفة.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

المثال التالي يوضح كيفية تعيين حد الذاكرة عند تحميل صورة JPEG. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// تعيين حد الذاكرة إلى 50 ميغابايت للصورة المحملة المستهدفة
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

### انظر أيضًا

* class [LoadOptions](../)
* namespace [Aspose.Imaging](../../loadoptions/)
* assembly [Aspose.Imaging](../../../)


