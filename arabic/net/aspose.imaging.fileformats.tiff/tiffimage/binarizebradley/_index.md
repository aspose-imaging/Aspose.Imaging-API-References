---
title: "TiffImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تنفيذ التحويل إلى ثنائي على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. هذه المقاربة تحسب عتبات محلية بشكل ديناميكي بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام المعالجة اللاحقة داخل تطبيقك."
type: docs
weight: 200
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/
---
## TiffImage.BinarizeBradley method

نفّذ التحويل إلى ثنائي على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. يحسب هذا النهج عتبات محلية ديناميكيًا بناءً على جوار الصورة، معززًا القدرة على التكيف مع ظروف الإضاءة المتغيرة وضمان تجزئة قوية للمهام اللاحقة داخل تطبيقك.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

## أمثلة

المثال التالي يحول صورة TIFF إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // حوّل الصورة إلى ثنائية مع فرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    tiffImage.BinarizeBradley(5, 10);
    tiffImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


