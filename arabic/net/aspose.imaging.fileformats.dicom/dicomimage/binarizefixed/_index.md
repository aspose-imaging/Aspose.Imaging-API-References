---
title: "DicomImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. تحويل الصورة بسهولة إلى صيغة ثنائية باستخدام عتبة محددة مسبقًا باستخدام هذه الطريقة المبسطة. مثالية للمطورين الذين يرغبون في تبسيط مهام معالجة الصور عن طريق تقسيم الصورة إلى مكونات المقدمة والخلفية بناءً على مستويات الشدة المحددة."
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

قم بتحويل الصورة إلى صيغة ثنائية بسهولة باستخدام عتبة محددة مسبقًا مع هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تبسيط مهام معالجة الصور عن طريق تقسيم الصورة إلى مكوّنات المقدمة والخلفية بناءً على مستويات الشدة المحددة.

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يقوم بتحويل صورة DICOM إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


