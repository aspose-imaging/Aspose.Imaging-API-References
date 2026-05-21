---
title: "فئة MagicWandTool"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.MagicWand.MagicWandTool. الفئة الخاصة بالمنطق الرئيسي لخوارزمية العصا السحرية"
type: docs
weight: 10930
url: /ar/net/aspose.imaging.magicwand/magicwandtool/
---
## MagicWandTool class

الفئة الخاصة بالمنطق الرئيسي لخوارزمية العصا السحرية.

```csharp
public class MagicWandTool : IPartialArgb32PixelLoader
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.imaging.magicwand/magicwandtool/process/)(Rectangle, int[], Point, Point) | يعالج البكسلات المحملة. |
| static [Select](../../aspose.imaging.magicwand/magicwandtool/select/)(RasterImage, MagicWandSettings) | ينشئ [`ImageBitMask`](../../aspose.imaging.magicwand.imagemasks/imagebitmask/) جديدًا استنادًا إلى [`MagicWandSettings`](../magicwandsettings/) وصورة المصدر [`RasterImage`](../../aspose.imaging/rasterimage/). |

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

يوضح المثال كيفية تحديد منطقة معقدة من صورة باستخدام أداة العصا السحرية والقدرة على التفاعل مع الأقنعة (عكس، اتحاد، طرح).

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على درجة اللون ولون البكسل (845, 128).
    MagicWandTool.Select(image, new MagicWandSettings(845, 128))
        // اتحاد القناع الموجود مع القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية.
        .Union(new MagicWandSettings(416, 387))
        // اعكس القناع الموجود.
        .Invert()
        // اطرح القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية مع العتبة المحددة من القناع الموجود.
        .Subtract(new MagicWandSettings(1482, 346) { Threshold = 69 })
        // اطرح أربعة أقنعة مستطيلة محددة من القناع الموجود واحدةً تلو الأخرى.
        .Subtract(new RectangleMask(0, 0, 800, 150))
        .Subtract(new RectangleMask(0, 380, 600, 220))
        .Subtract(new RectangleMask(930, 520, 110, 40))
        .Subtract(new RectangleMask(1370, 400, 120, 200))
        // تنعيم القناع بالإعدادات المحددة.
        .GetFeathered(new FeatheringSettings() { Size = 3 })
        // طبق القناع على الصورة.
        .Apply();
        
    // احفظ الصورة.
    image.Save(outputFilePath);
}
```

### انظر أيضًا

* interface [IPartialArgb32PixelLoader](../../aspose.imaging/ipartialargb32pixelloader/)
* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


