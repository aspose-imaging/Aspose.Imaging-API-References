---
title: "الفئة FeatheringSettings"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.MagicWand.ImageMasks.FeatheringSettings. فئة إعدادات الريش"
type: docs
weight: 10850
url: /ar/net/aspose.imaging.magicwand.imagemasks/featheringsettings/
---
## FeatheringSettings class

فئة إعدادات التريش.

```csharp
public class FeatheringSettings
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FeatheringSettings](featheringsettings/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Mode](../../aspose.imaging.magicwand.imagemasks/featheringsettings/mode/) { get; set; } | يحصل أو يضبط وضع خوارزمية الريش. |
| [Size](../../aspose.imaging.magicwand.imagemasks/featheringsettings/size/) { get; set; } | يحصل أو يضبط حجم الريش. |

## أمثلة

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

* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


