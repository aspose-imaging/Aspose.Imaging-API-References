---
title: "RasterImage.Dither"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تنفّذ التنقيط على الصورة الحالية."
type: docs
weight: 280
url: /ar/net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

يقوم بأداء التمويه على الصورة الحالية.

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة dithering. |
| bitsCount | Int32 | عدد البتات النهائي للتمويه. |
| customPalette | IColorPalette | لوحة الألوان المخصصة للتمويه. |

### انظر أيضًا

* enum [DitheringMethod](../../ditheringmethod/)
* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

يقوم بأداء التمويه على الصورة الحالية.

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة dithering. |
| bitsCount | Int32 | عدد البتات النهائي للتمويه. |

## أمثلة

المثال التالي يحمل صورة نقطية ويجري تلطيـف العتبة و Floyd باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### انظر أيضًا

* enum [DitheringMethod](../../ditheringmethod/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


