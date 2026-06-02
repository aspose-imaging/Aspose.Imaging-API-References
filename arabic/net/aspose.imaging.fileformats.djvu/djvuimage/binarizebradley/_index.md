---
title: "DjvuImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. التحويل إلى ثنائي باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو أسلوب يحسب عتبة محلية لكل بكسل بناءً على الجوار المحلي. يتكيف مع تغيرات الإضاءة عبر الصورة مما يجعله مناسبًا للصور ذات الإضاءة غير المتساوية. من خلال حساب العتبة باستخدام الصور المتكاملة يتعامل بكفاءة مع أجواء واسعة مما يجعله قابلًا للتطبيق في التطبيقات الفورية. تُستخدم هذه التقنية عادةً في معالجة المستندات OCR (التعرف الضوئي على الأحرف) وتقسيم الصور حيث يكون التحويل إلى ثنائي الدقة ضروريًا للتحليل اللاحق"
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/
---
## DjvuImage.BinarizeBradley method

التصنيف الثنائي باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو طريقة تحسب عتبة محلية لكل بكسل بناءً على الجوار المحلي. تتكيف مع تغيرات الإضاءة عبر الصورة، مما يجعلها مناسبة للصور ذات ظروف إضاءة غير متساوية. من خلال حساب العتبة باستخدام الصور المتكاملة، تتعامل بكفاءة مع أجواء كبيرة، مما يجعلها قابلة للتطبيق في التطبيقات الفورية. تُستخدم هذه التقنية عادةً في معالجة المستندات، والتعرف الضوئي على الأحرف (OCR)، ومهام تجزئة الصور حيث يكون التصنيف الثنائي الدقيق ضروريًا للتحليل اللاحق.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

## أمثلة

المثال التالي يحول صورة DJVU إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع حجم النافذة المحدد. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // حوّل الصورة إلى ثنائية مع فرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    djvuImage.BinarizeBradley(5, 10);
    djvuImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


