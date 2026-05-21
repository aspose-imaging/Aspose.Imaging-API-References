---
title: "DicomImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. ثنِّ الصور باستخدام خوارزمية العتبة التكيفية لبرادلي التي تستفيد من عتبة الصورة المتكاملة لتحسين الأداء. مثالي للمطورين الذين يرغبون في تقسيم الصور تلقائيًا بناءً على التباينات المحلية في السطوع لضمان اكتشاف واستخراج كائنات دقيقة في ظروف إضاءة متغيرة."
type: docs
weight: 140
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/
---
## DicomImage.BinarizeBradley method

تحويل الصور إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي، مستفيدًا من عتبة الصورة المتكاملة لتحسين الأداء. مثالي للمطورين الذين يرغبون في تقسيم الصور تلقائيًا بناءً على التباينات المحلية في السطوع، مما يضمن اكتشافًا واستخراجًا دقيقًا للكائنات في ظروف إضاءة متغيرة.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

## أمثلة

المثال التالي يحول صورة DICOM إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // حوّل الصورة إلى ثنائية مع فرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    dicomImage.BinarizeBradley(5, 10);
    dicomImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


