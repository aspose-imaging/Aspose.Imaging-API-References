---
title: "الفئة WatermarkRemover"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Watermark.WatermarkRemover. الفئة مخصصة لمعالجة العلامة المائية"
type: docs
weight: 11860
url: /ar/net/aspose.imaging.watermark/watermarkremover/
---
## WatermarkRemover class

الفئة مخصصة لتعديل Watermark.

```csharp
public static class WatermarkRemover
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [PaintOver](../../aspose.imaging.watermark/watermarkremover/paintover/)(RasterImage, WatermarkOptions) | إزالة العلامة المائية من الصورة النقطية. |

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

* namespace [Aspose.Imaging.Watermark](../../aspose.imaging.watermark/)
* assembly [Aspose.Imaging](../../)


