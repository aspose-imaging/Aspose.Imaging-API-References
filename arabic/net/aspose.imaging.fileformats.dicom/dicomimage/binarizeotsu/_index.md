---
title: "DicomImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. تطبيق عتبة Otsu لتصنيف الصورة إلى ثنائية تلقائيًا مع تحديد القيمة المثلى للعتبة بناءً على هيستوغرام الصورة. مثالية للمطورين الذين يبحثون عن طريقة موثوقة لتقسيم الصور إلى مناطق المقدمة والخلفية بأقل تدخل يدوي."
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/
---
## DicomImage.BinarizeOtsu method

طبق عتبة أوتو لتثبيت الصورة، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوجرام الصورة. مثالي للمطورين الباحثين عن طريقة موثوقة لتقسيم الصور إلى مناطق المقدمة والخلفية بأقل تدخل يدوي.

```csharp
public override void BinarizeOtsu()
```

## أمثلة

المثال التالي يصنف صورة DICOM إلى ثنائية باستخدام عتبة Otsu. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    dicomImage.BinarizeOtsu();
    dicomImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


