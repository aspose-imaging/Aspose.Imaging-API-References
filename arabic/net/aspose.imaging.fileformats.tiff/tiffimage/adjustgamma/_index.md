---
title: "TiffImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تطبيق تصحيح جاما على الصورة مع تعديل شدة البكسلات لتحقيق توازن لوني مرغوب. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز جودة الصورة وتحسين دقة التحليل اللاحق أو مهام العرض داخل تطبيقك"
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

طبق تصحيح جاما على الصورة، معدلاً شدة البكسلات لتحقيق توازن لوني مطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لتحسين الجودة البصرية وزيادة دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك.

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gamma | فردي | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

## أمثلة

المثال التالي يقوم بإجراء تصحيح جاما لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // اضبط معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.AdjustGamma(2.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

نفّذ تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور لتحقيق تحكم دقيق في عرض الألوان وتعزيز الدقة البصرية داخل تطبيقك.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | فردي | معامل جاما للقناة الحمراء |
| gammaGreen | فردي | معامل جاما للقناة الخضراء |
| gammaBlue | فردي | معامل جاما للقناة الزرقاء |

## أمثلة

المثال التالي يقوم بإجراء تصحيح جاما لصورة TIFF باستخدام معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // اضبط معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


