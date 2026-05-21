---
title: "TiffImage.Dither"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تنفيذ التدرج (dithering) على الصورة الحالية لتحسين جودتها البصرية وتقليل آثار تدرج الألوان. دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات أكثر سلاسة بين الألوان، مما ينتج مظهرًا عامًّا محسّنًا للصورة ووضوحًا أعلى."
type: docs
weight: 240
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/dither/
---
## TiffImage.Dither method

نفّذ التدرج الضبابي على الصورة الحالية لتحسين جودتها البصرية وتقليل آثار تدرج الألوان. دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات أكثر سلاسة بين الألوان، مما ينتج مظهرًا عامًّا محسّنًا للصورة ووضوحًا أعلى.

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

المثال التالي يحمل صورة TIFF ويجري تطبيق عتبة وتدرج فلويد باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


