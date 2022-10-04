---
title: BinarizeFixed
second_title: Aspose.Imaging لمرجع NET API
description: ثنائية الصورة مع عتبة محددة مسبقًا
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

ثنائية الصورة مع عتبة محددة مسبقًا

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| threshold | Byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة ، فسيتم تعيين قيمة 255 لها ، وإلا فسيتم تعيين 0. |

### أمثلة

يقوم المثال التالي بترميز صورة TIFF إلى قيم ثنائية باستخدام الحد المحدد مسبقًا. تحتوي الصور الثنائية على لونين فقط - أبيض وأسود.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // ثنائياً للصورة بقيمة حد 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127 ، فسيتم تعيين قيمة 255 لها ، وإلا فسيتم تعيين 0.
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->