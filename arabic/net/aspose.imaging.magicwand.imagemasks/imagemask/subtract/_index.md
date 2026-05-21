---
title: "ImageMask.Subtract"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageMask. يحصل على نتيجة طرح القناع المقدم من الحالي"
type: docs
weight: 190
url: /ar/net/aspose.imaging.magicwand.imagemasks/imagemask/subtract/
---
## Subtract(ImageMask) {#subtract}

يحصل على طرح القناع المقدم من القناع الحالي.

```csharp
public ImageBitMask Subtract(ImageMask mask)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قناع | ImageMask | القناع المقدم |

### قيمة الإرجاع

جديد [`ImageBitMask`](../../imagebitmask/).

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

* class [ImageBitMask](../../imagebitmask/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Subtract(MagicWandSettings) {#subtract_1}

يحصل على نتيجة تحديد العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع.

```csharp
public ImageBitMask Subtract(MagicWandSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الإعدادات | MagicWandSettings | إعدادات العصا السحرية. |

### قيمة الإرجاع

جديد [`ImageBitMask`](../../imagebitmask/).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما لا تكون صورة المصدر معرفة في القناع. |

### انظر أيضًا

* class [ImageBitMask](../../imagebitmask/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Subtract(RasterImage, MagicWandSettings) {#subtract_2}

يحصل على نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي.

```csharp
public ImageBitMask Subtract(RasterImage image, MagicWandSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | صورة للعصا السحرية. |
| الإعدادات | MagicWandSettings | إعدادات العصا السحرية. |

### قيمة الإرجاع

جديد [`ImageBitMask`](../../imagebitmask/).

### انظر أيضًا

* class [ImageBitMask](../../imagebitmask/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


