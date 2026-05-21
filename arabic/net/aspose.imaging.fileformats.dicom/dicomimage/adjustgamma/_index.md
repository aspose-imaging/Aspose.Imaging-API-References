---
title: "DicomImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. حسّن جودة الصورة واضبطها باستخدام تصحيح جاما، وهي تقنية قوية لضبط المظهر البصري. مثالية للمطورين الذين يهدفون إلى تحسين عرض الصورة، وضبط توازن الألوان، وضمان عرض متسق عبر الأجهزة والبيئات المختلفة."
type: docs
weight: 130
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

حسّن جودة الصورة واضبطها باستخدام تصحيح جاما، وهي تقنية قوية لضبط المظهر البصري بدقة. مثالية للمطورين الذين يهدفون إلى تحسين عرض الصورة، وضبط توازن الألوان، وضمان عرض متسق عبر مختلف الأجهزة والبيئات.

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gamma | فردي | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

## أمثلة

المثال التالي ينفّذ تصحيح جاما لصورة DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // اضبط معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    dicomImage.AdjustGamma(2.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

تحقق من تعديلات ألوان دقيقة من خلال تطبيق تصحيح جاما بشكل مستقل على مكونات الأحمر والأخضر والأزرق في الصورة. تضمن هذه الطريقة توازنًا لونيًا دقيقًا ومخرجات بصرية مثالية، لتلبية احتياجات المطورين الذين يسعون إلى تحكم دقيق في عرض الصورة ودقة الألوان.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | فردي | معامل جاما للقناة الحمراء |
| gammaGreen | فردي | معامل جاما للقناة الخضراء |
| gammaBlue | فردي | معامل جاما للقناة الزرقاء |

## أمثلة

المثال التالي ينفّذ تصحيح جاما لصورة DICOM مع تطبيق معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // اضبط معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    dicomImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


