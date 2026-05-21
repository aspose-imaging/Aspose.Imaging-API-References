---
title: "الفئة ContentAwareFillWatermarkOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Watermark.Options.ContentAwareFillWatermarkOptions. الخيارات العامة لخوارزمية ملء المحتوى الذكي."
type: docs
weight: 11830
url: /ar/net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
## ContentAwareFillWatermarkOptions class

خيارات خوارزمية التعبئة المدركة للمحتوى الشائعة.

```csharp
public class ContentAwareFillWatermarkOptions : WatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor)(GraphicsPath) | ينشئ مثيلاً جديدًا للفئة `ContentAwareFillWatermarkOptions`. |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor_1)(Point[]) | ينشئ مثيلاً جديدًا للفئة `ContentAwareFillWatermarkOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | تحصل أو تعين القناع. |
| [InterestArea](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/interestarea/) { get; set; } | يحصل أو يعيّن المنطقة التي تُؤخذ منها الرقع. |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | تحصل أو تعين القناع. |
| [MaxPaintingAttempts](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد محاولات الرسم. ستختار الخوارزمية المتغيّر الأفضل. |
| [PatchSize](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/patchsize/) { get; set; } | يحصل أو يعيّن حجم الرقعة (يجب أن يكون فرديًا). |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث تقدم عملية ما قبل حساب النقاط الافتراضية. |

## أمثلة

يوضح المثال كيفية إزالة أي كائن من الصورة باستخدام Graphics Path مع خوارزمية Content Aware fill.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new ContentAwareFillWatermarkOptions(mask) 
    { 
        MaxPaintingAttempts = 4
    };

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

### انظر أيضًا

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


