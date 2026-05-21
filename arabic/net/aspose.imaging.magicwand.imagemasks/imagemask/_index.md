---
title: "الفئة ImageMask"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.MagicWand.ImageMasks.ImageMask. يصف قناع صورة ثنائي."
type: docs
weight: 10890
url: /ar/net/aspose.imaging.magicwand.imagemasks/imagemask/
---
## ImageMask class

يصف قناع صورة ثنائي.

```csharp
public abstract class ImageMask : IImageMask
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds/) { get; } | يحصل على حدود هذا القناع، بوحدات البكسل. |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height/) { get; } | يحصل على ارتفاع هذا القناع، بوحدات البكسل. |
| abstract [Item](../../aspose.imaging.magicwand.imagemasks/imagemask/item/) { get; } | يحصل على شفافية البكسل المحدد. |
| abstract [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/imagemask/selectionbounds/) { get; } | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source/) { get; } | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا وجدت. |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width/) { get; } | يحصل على عرض هذا القناع، بوحدات البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply/)() | يطبق القناع الحالي على مصدر [`RasterImage`](../../aspose.imaging/rasterimage/) إذا كان موجودًا. |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto/)(RasterImage) | يطبق القناع الحالي على [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد. |
| abstract [Clone](../../aspose.imaging.magicwand.imagemasks/imagemask/clone/)() | ينشئ كائنًا جديدًا يكون نسخة من النسخة الحالية. |
| abstract [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop)(Rectangle) | يقص القناع بالمستطيل المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop_1)(Size) | يقص القناع بالحجم المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop_2)(int, int) | يقص القناع بالعرض والارتفاع المحددين. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction)(ImageMask) | يحصل على الفرق الحصري بين القناع الحالي والمقدم. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction_1)(MagicWandSettings) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction_2)(RasterImage, MagicWandSettings) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة. |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity/)(int, int) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered/)(FeatheringSettings) | يحصل على قناع رمادي مع تمويه الحدود وفق الإعدادات المحددة. |
| abstract [Inflate](../../aspose.imaging.magicwand.imagemasks/imagemask/inflate/)(int) | يوسع هذا القناع بالمقدار المحدد. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect)(ImageMask) | يحصل على تقاطع القناع الحالي مع المقدم. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect_1)(MagicWandSettings) | يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect_2)(RasterImage, MagicWandSettings) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagemask/invert/)() | يحصل على عكس القناع الحالي. |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagemask/isopaque/)(int, int) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagemask/istransparent/)(int, int) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract)(ImageMask) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract_1)(MagicWandSettings) | يحصل على نتيجة تحديد العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract_2)(RasterImage, MagicWandSettings) | يحصل على نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union)(ImageMask) | يحصل على اتحاد القناع الحالي مع القناع المقدم. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union_1)(MagicWandSettings) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union_2)(RasterImage, MagicWandSettings) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [operator +](../../aspose.imaging.magicwand.imagemasks/imagemask/op_addition/) | اتحاد قناعين. |
| [operator ^](../../aspose.imaging.magicwand.imagemasks/imagemask/op_exclusiveor/) | التفريق الحصري لقناعين. |
| [explicit operator](../../aspose.imaging.magicwand.imagemasks/imagemask/op_explicit/) | [`ImageGrayscaleMask`](../imagegrayscalemask/) مشغل التحويل. |
| [operator !](../../aspose.imaging.magicwand.imagemasks/imagemask/op_logicalnot/) | يعكس القناع. |
| [operator *](../../aspose.imaging.magicwand.imagemasks/imagemask/op_multiply/) | تقاطع قناعين. |
| [operator -](../../aspose.imaging.magicwand.imagemasks/imagemask/op_subtraction/) | اطرح القناع الثاني من الأول. |

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

* interface [IImageMask](../iimagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


