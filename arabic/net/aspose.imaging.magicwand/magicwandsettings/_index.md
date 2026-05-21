---
title: "الفئة MagicWandSettings"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.MagicWand.MagicWandSettings. فئة إعدادات اختيار العصا السحرية."
type: docs
weight: 10910
url: /ar/net/aspose.imaging.magicwand/magicwandsettings/
---
## MagicWandSettings class

فئة إعدادات اختيار العصا السحرية.

```csharp
public class MagicWandSettings
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MagicWandSettings](magicwandsettings/#constructor)(Point) | ينشئ مثيلاً جديدًا للفئة `MagicWandSettings`. |
| [MagicWandSettings](magicwandsettings/#constructor_1)(int, int) | ينشئ مثيلاً جديدًا للفئة `MagicWandSettings`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AreaOfInterest](../../aspose.imaging.magicwand/magicwandsettings/areaofinterest/) { get; set; } | يحصل أو يعيّن حدود المنطقة لعمل الخوارزمية. |
| [ColorCompareMode](../../aspose.imaging.magicwand/magicwandsettings/colorcomparemode/) { get; set; } | يحصل أو يعيّن طريقة مقارنة الألوان في الخوارزمية. |
| [ColorComparisonDelegate](../../aspose.imaging.magicwand/magicwandsettings/colorcomparisondelegate/) { get; set; } | يحصل أو يعيّن خوارزمية مقارنة الألوان المخصّصة إذا تم تعيين [`ColorCompareMode`](./colorcomparemode/) إلى Custom. |
| [ContiguousMode](../../aspose.imaging.magicwand/magicwandsettings/contiguousmode/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت العصا السحرية ستحدد فقط البكسلات المتجاورة. |
| [DirectionalMode](../../aspose.imaging.magicwand/magicwandsettings/directionalmode/) { get; set; } | يحصل أو يعيّن وضع خوارزمية البحث بالملء المتدفّق: بحث بأربع أو ثمان اتجاهات. |
| [Point](../../aspose.imaging.magicwand/magicwandsettings/point/) { get; } | يحصل أو يعيّن نقطة المرجع لعمل الخوارزمية. |
| [Threshold](../../aspose.imaging.magicwand/magicwandsettings/threshold/) { get; set; } | يحصل أو يعيّن مستوى التحمل لمقارنة ألوان البكسلات. |

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

* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


