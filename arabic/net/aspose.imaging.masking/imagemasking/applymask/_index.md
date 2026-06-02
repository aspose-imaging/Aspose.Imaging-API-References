---
title: "ImageMasking.ApplyMask"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageMasking. تُطبق القناع على الصورة المصدر المحددة"
type: docs
weight: 60
url: /ar/net/aspose.imaging.masking/imagemasking/applymask/
---
## ImageMasking.ApplyMask method

يطبق القناع على الصورة المصدر المحددة.

```csharp
public static void ApplyMask(RasterImage targetImage, RasterImage mask, 
    MaskingOptions maskingOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetImage | RasterImage | صورة الهدف. |
| قناع | RasterImage | صورة القناع التي سيتم تطبيقها. |
| maskingOptions | MaskingOptions | خيارات القناع. |

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

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MaskingOptions](../../../aspose.imaging.masking.options/maskingoptions/)
* class [ImageMasking](../)
* namespace [Aspose.Imaging.Masking](../../imagemasking/)
* assembly [Aspose.Imaging](../../../)


