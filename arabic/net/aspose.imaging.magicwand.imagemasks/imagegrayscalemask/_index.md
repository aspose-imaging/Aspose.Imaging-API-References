---
title: "الفئة ImageGrayscaleMask"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.MagicWand.ImageMasks.ImageGrayscaleMask. يصف قناع صورة بتدرج الرمادي"
type: docs
weight: 10880
url: /ar/net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
## ImageGrayscaleMask class

يصف قناع صورة بتدرج الرمادي.

```csharp
public class ImageGrayscaleMask : IImageMask
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor)(RasterImage) | ينشئ مثيلًا جديدًا للفئة `ImageGrayscaleMask` بالحجم المستند إلى [`RasterImage`](../../aspose.imaging/rasterimage/) الموجود المحدد. سيتم تخزين [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد كصورة مصدر. |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor_1)(int, int) | ينشئ مثيلًا جديدًا للفئة `ImageGrayscaleMask` باستخدام العرض والارتفاع المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/bounds/) { get; } | يحصل على حدود هذا القناع، بوحدات البكسل. |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/height/) { get; } | يحصل على ارتفاع هذا القناع، بوحدات البكسل. |
| [Item](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/item/) { get; set; } | يحصل أو يضبط شفافية البكسل المحدد. |
| [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/selectionbounds/) { get; } | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/source/) { get; } | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا وجدت. |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/width/) { get; } | يحصل على عرض هذا القناع، بوحدات البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/apply/)() | يطبق القناع الحالي على مصدر [`RasterImage`](../../aspose.imaging/rasterimage/) إذا كان موجودًا. |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/applyto/)(RasterImage) | يطبق القناع الحالي على [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد. |
| [Clone](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/clone/)() | ينشئ كائنًا جديدًا يكون نسخة من النسخة الحالية. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop)(Rectangle) | يقص القناع بالمستطيل المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_1)(Size) | يقص القناع بالحجم المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_2)(int, int) | يقص القناع بالعرض والارتفاع المحددين. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/exclusivedisjunction/)(ImageGrayscaleMask) | يحصل على الفرق الحصري بين القناع الحالي والمقدم. |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/getbyteopacity/)(int, int) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/intersect/)(ImageGrayscaleMask) | يحصل على تقاطع القناع الحالي مع المقدم. |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/invert/)() | يحصل على عكس القناع الحالي. |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/isopaque/)(int, int) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/istransparent/)(int, int) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/subtract/)(ImageGrayscaleMask) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/union/)(ImageGrayscaleMask) | اتحاد قناعين. |
| [operator +](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_addition/) | اتحاد قناعين. |
| [operator ^](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_exclusiveor/) | التفريق الحصري لقناعين. |
| [operator !](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_logicalnot/) | يعكس القناع. |
| [operator *](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_multiply/) | تقاطع قناعين. |
| [operator -](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_subtraction/) | اطرح القناع الثاني من الأول. |

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


