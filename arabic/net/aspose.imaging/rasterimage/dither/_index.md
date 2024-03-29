---
title: Dither
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بالتردد على الصورة الحالية.
type: docs
weight: 260
url: /ar/net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

يقوم بالتردد على الصورة الحالية.

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة التردد. |
| bitsCount | Int32 | البتات النهائية تحسب للتردد. |
| customPalette | IColorPalette | اللوحة المخصصة لثبات الألوان. |

### أنظر أيضا

* enum [DitheringMethod](../../ditheringmethod)
* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

يقوم بالتردد على الصورة الحالية.

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة التردد. |
| bitsCount | Int32 | البتات النهائية تحسب للتردد. |

### أمثلة

يحمّل المثال التالي صورة نقطية وينفذ ثبات الألوان في الحد الفاصل وتدرج الألوان باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بإجراء ثبات الألوان باستخدام لوحة ألوان من 4 بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة للجودة الأعلى والحجم الأكبر للصورة الناتجة.
    // لاحظ أنه يتم دعم لوحات 1 بت و 4 بت و 8 بت فقط في الوقت الحالي.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بإجراء ثبات الألوان فلويد باستخدام لوحة ألوان 1 بت تحتوي على لونين فقط - أبيض وأسود.
    // كلما زاد عدد البتات المحددة للجودة الأعلى والحجم الأكبر للصورة الناتجة.
    // لاحظ أنه يتم دعم لوحات 1 بت و 4 بت و 8 بت فقط في الوقت الحالي.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### أنظر أيضا

* enum [DitheringMethod](../../ditheringmethod)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
