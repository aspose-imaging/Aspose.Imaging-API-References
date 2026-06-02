---
title: "ImageMask.Apply"
second_title: "Aspose.Imaging for .NET API Reference"
description: "ImageMask method. يطبق القناع الحالي على مصدر RasterImage إذا كان موجودًا"
type: docs
weight: 70
url: /ar/net/aspose.imaging.magicwand.imagemasks/imagemask/apply/
---
## ImageMask.Apply method

يطبق القناع الحالي على مصدر [`RasterImage`](../../../aspose.imaging/rasterimage/)، إذا كان موجودًا.

```csharp
public void Apply()
```

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| NullReferenceException | يُرمى عندما لا تكون صورة المصدر معرفة. |

## أمثلة

يوضح المثال كيفية تحديد منطقة بسيطة من صورة بناءً على النغمة واللون لأي بكسل باستخدام أداة Magic Wand.

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة magic wand بناءً على نغمة ولون البكسل (120, 100) مع عتبة مخصصة تساوي 150.
    MagicWandTool
        .Select(image, new MagicWandSettings(120, 100) { Threshold = 150 })
        // طبق القناع على الصورة.
        .Apply();

    // احفظ الصورة مع خيار نوع لون الشفافية القسري.
    image.Save(outputFilePath, new ImageOptions.PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### انظر أيضًا

* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


