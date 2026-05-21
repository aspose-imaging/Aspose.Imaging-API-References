---
title: "GifImage.Dither"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تطبيق التمويه dithering على الصورة الحالية. تعزز هذه العملية جودة الصورة عن طريق تقليل تدرج الألوان وتحسين الانتقالات اللونية مما ينتج مظهرًا أكثر سلاسة"
type: docs
weight: 290
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/dither/
---
## GifImage.Dither method

طبق التمويه على الصورة الحالية. تعزز هذه العملية جودة الصورة عن طريق تقليل تدرجات اللون وتحسين الانتقالات اللونية، مما ينتج مظهرًا أكثر سلاسة.

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

المثال التالي يحمل صورة GIF ويجري تطبيق عتبة وتمويه Floyd باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


