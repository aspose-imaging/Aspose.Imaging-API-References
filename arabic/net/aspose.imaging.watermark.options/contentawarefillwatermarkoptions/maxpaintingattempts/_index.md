---
title: "ContentAwareFillWatermarkOptions.MaxPaintingAttempts"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ContentAwareFillWatermarkOptions. يحصل أو يعيّن الحد الأقصى لعدد محاولات الرسم. ستختار الخوارزمية المتغيّر الأفضل"
type: docs
weight: 30
url: /ar/net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/
---
## ContentAwareFillWatermarkOptions.MaxPaintingAttempts property

يحصل أو يعيّن الحد الأقصى لعدد محاولات الرسم. ستختار الخوارزمية المتغيّر الأفضل.

```csharp
public int MaxPaintingAttempts { get; set; }
```

### Property Value

الحد الأقصى لعدد محاولات الرسم.

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

* class [ContentAwareFillWatermarkOptions](../)
* namespace [Aspose.Imaging.Watermark.Options](../../contentawarefillwatermarkoptions/)
* assembly [Aspose.Imaging](../../../)


