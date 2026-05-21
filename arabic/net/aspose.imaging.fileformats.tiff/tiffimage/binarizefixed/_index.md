---
title: "TiffImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تطبيق التحويل إلى ثنائي على الصورة باستخدام عتبة محددة مسبقًا، مما يحولها إلى صورة ثنائية ذات مناطق مقدمة وخلفية متميزة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز دقة وكفاءة تحليل الصور داخل تطبيقك."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

طبق التحويل إلى ثنائي على الصورة باستخدام عتبة محددة مسبقًا، محولًا إياها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة. دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، معززًا دقة وكفاءة تحليل الصور داخل تطبيقك.

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يحول صورة TIFF إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


