---
title: "DjvuImage.Dither"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تقوم وظيفة Dither بتطبيق تأثير التمويه على صورتك مما يحسن جودتها البصرية عن طريق تقليل التدرجات الحادة وتحسين انتقالات الألوان. سواءً كنت تعمل على فنون رقمية أو تصوير أو مشاريع تصميم جرافيكي، فإن هذه الميزة تضيف لمسة احترافية لصورك تجعلها تبدو أكثر سلاسة وتفصيلاً."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/dither/
---
## DjvuImage.Dither method

وظيفة \"Dither\" تطبق تأثير التدرج المتناثر على صورتك، مما يعزز جودتها البصرية عن طريق تقليل التدرجات الحادة وتحسين انتقالات الألوان. سواءً كنت تعمل على فن رقمي، أو تصوير فوتوغرافي، أو مشاريع تصميم جرافيكي، فإن هذه الميزة تضيف لمسة احترافية لصورك، تجعلها تبدو أكثر سلاسة وتفصيلًا.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة dithering. |
| bitsCount | Int32 | عدد البتات النهائي للتمويه. |
| customPalette | IColorPalette | لوحة الألوان المخصصة للتمويه. |

## أمثلة

المثال التالي يحمل صورة DJVU ويجري تطبيق عتبة وتلوين فلويد باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


