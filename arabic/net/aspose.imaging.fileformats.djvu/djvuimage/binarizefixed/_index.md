---
title: "DjvuImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. التحويل إلى ثنائي باستخدام عتبة محددة مسبقًا يبسط الصور المعقدة إلى تمثيلات ثنائية حيث يتم تصنيف البكسلات إما كالسوداء أو البيضاء بناءً على شدة الإضاءة مقارنةً بقيمة العتبة المحددة. تُستخدم هذه التقنية عادةً في معالجة الصور لتعزيز الوضوح وتبسيط التحليل وتحضير الصور لمراحل معالجة إضافية مثل التعرف الضوئي على الأحرف OCR. من خلال تطبيق عتبة ثابتة يمكنك تحويل صور التدرج الرمادي بسرعة إلى شكل ثنائي مما يجعلها أسهل في الفهم واستخلاص المعلومات ذات المعنى."
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/
---
## DjvuImage.BinarizeFixed method

التصنيف الثنائي باستخدام عتبة محددة مسبقًا يبسط الصور المعقدة إلى تمثيلات ثنائية، حيث يتم تصنيف البكسلات إما كالسوداء أو الأبيض بناءً على شدة إضاءةها مقارنةً بقيمة العتبة المحددة. تُستخدم هذه التقنية عادةً في معالجة الصور لتعزيز الوضوح، وتبسيط التحليل، وإعداد الصور للخطوات اللاحقة مثل التعرف الضوئي على الأحرف (OCR). من خلال تطبيق عتبة ثابتة، يمكنك تحويل الصور ذات التدرج الرمادي إلى شكل ثنائي بسرعة، مما يجعلها أسهل في الفهم واستخراج المعلومات ذات الأهمية.

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يحول صورة DJVU إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


