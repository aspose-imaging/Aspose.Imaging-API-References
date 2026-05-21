---
title: "TiffImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. استخدم عتبة Otsu لإجراء التحويل الثنائي على الصورة مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوجرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة فعالة واستخراج ميزات يعزز دقة وموثوقية مهام تحليل الصور داخل تطبيقك."
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

استخدم عتبة أوتسو لإجراء التحويل إلى ثنائي على الصورة، محددًا تلقائيًا قيمة العتبة المثلى بناءً على هيستوغرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة فعّالة واستخراج ميزات، معززًا دقة وموثوقية مهام تحليل الصور داخل تطبيقك.

```csharp
public override void BinarizeOtsu()
```

## أمثلة

المثال التالي يحول صورة TIFF إلى ثنائية باستخدام عتبة Otsu. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


