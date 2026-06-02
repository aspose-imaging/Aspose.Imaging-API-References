---
title: "الفئة TeleaWatermarkOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Watermark.Options.TeleaWatermarkOptions. الخيارات العامة لخوارزمية Telea"
type: docs
weight: 11840
url: /ar/net/aspose.imaging.watermark.options/teleawatermarkoptions/
---
## TeleaWatermarkOptions class

خيارات خوارزمية Telea الشائعة.

```csharp
public class TeleaWatermarkOptions : WatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor)(GraphicsPath) | يقوم بتهيئة نسخة جديدة من الفئة `TeleaWatermarkOptions`. |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor_1)(Point[]) | يقوم بتهيئة نسخة جديدة من الفئة `TeleaWatermarkOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | تحصل أو تعين القناع. |
| [HalfPatchSize](../../aspose.imaging.watermark.options/teleawatermarkoptions/halfpatchsize/) { get; set; } | يحصل أو يعيّن حجم نصف الرقعة. |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | تحصل أو تعين القناع. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث تقدم عملية ما قبل حساب النقاط الافتراضية. |

## أمثلة

يوضح المثال كيفية إزالة أي كائن من الصورة باستخدام Graphics Path مع خوارزمية Telea.

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

    var options = new TeleaWatermarkOptions(mask);

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

### انظر أيضًا

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


