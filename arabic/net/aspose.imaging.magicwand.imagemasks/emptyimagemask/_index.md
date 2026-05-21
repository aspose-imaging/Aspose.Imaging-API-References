---
title: "الفئة EmptyImageMask"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.MagicWand.ImageMasks.EmptyImageMask. يصف قناعًا فارغًا غير مجرد"
type: docs
weight: 10830
url: /ar/net/aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
## EmptyImageMask class

يصف قناعًا فارغًا غير مجرد.

```csharp
public class EmptyImageMask : ImageMask
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmptyImageMask](emptyimagemask/)(int, int) | ينشئ مثيلًا جديدًا للفئة `EmptyImageMask` باستخدام العرض والارتفاع المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds/) { get; } | يحصل على حدود هذا القناع، بوحدات البكسل. |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height/) { get; } | يحصل على ارتفاع هذا القناع، بوحدات البكسل. |
| override [Item](../../aspose.imaging.magicwand.imagemasks/emptyimagemask/item/) { get; } | يحصل على شفافية البكسل المحدد. |
| override [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/emptyimagemask/selectionbounds/) { get; } | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source/) { get; } | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا وجدت. |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width/) { get; } | يحصل على عرض هذا القناع، بوحدات البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply/)() | يطبق القناع الحالي على مصدر [`RasterImage`](../../aspose.imaging/rasterimage/) إذا كان موجودًا. |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto/)(RasterImage) | يطبق القناع الحالي على [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد. |
| override [Clone](../../aspose.imaging.magicwand.imagemasks/emptyimagemask/clone/)() | ينشئ كائنًا جديدًا يكون نسخة من النسخة الحالية. |
| override [Crop](../../aspose.imaging.magicwand.imagemasks/emptyimagemask/crop/#crop)(Rectangle) | يقص القناع بالمستطيل المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(Size) | يقص القناع بالحجم المحدد. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(int, int) | يقص القناع بالعرض والارتفاع المحددين. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(ImageMask) | يحصل على الفرق الحصري بين القناع الحالي والمقدم. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(MagicWandSettings) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(RasterImage, MagicWandSettings) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة. |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity/)(int, int) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered/)(FeatheringSettings) | يحصل على قناع رمادي مع تمويه الحدود وفق الإعدادات المحددة. |
| override [Inflate](../../aspose.imaging.magicwand.imagemasks/emptyimagemask/inflate/)(int) | يوسع هذا القناع بالمقدار المحدد. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(ImageMask) | يحصل على تقاطع القناع الحالي مع المقدم. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(MagicWandSettings) | يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(RasterImage, MagicWandSettings) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagemask/invert/)() | يحصل على عكس القناع الحالي. |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagemask/isopaque/)(int, int) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagemask/istransparent/)(int, int) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(ImageMask) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(MagicWandSettings) | يحصل على نتيجة تحديد العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(RasterImage, MagicWandSettings) | يحصل على نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(ImageMask) | يحصل على اتحاد القناع الحالي مع القناع المقدم. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(MagicWandSettings) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(RasterImage, MagicWandSettings) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |

### انظر أيضًا

* class [ImageMask](../imagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


