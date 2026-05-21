---
title: "DicomImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. قم بتحويل الصور بسهولة إلى تمثيلها الرمادي مما يبسط التحليل البصري ومهام المعالجة. مثالية للمطورين الذين يرغبون في تحسين وضوح الصورة، تقليل التعقيد وتسهيل الخوارزميات القائمة على التدرج الرمادي الفعّالة لتطبيقات متنوعة."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/grayscale/
---
## DicomImage.Grayscale method

حوّل الصور بسهولة إلى تمثيلها بتدرج الرمادي، مما يبسط تحليل الصور ومعالجة المهام. مثالي للمطورين الذين يسعون لتحسين وضوح الصورة، تقليل التعقيد، وتسهيل الخوارزميات القائمة على التدرج الرمادي لتطبيقات متنوعة.

```csharp
public override void Grayscale()
```

## أمثلة

المثال التالي يحول صورة DICOM ملونة إلى تمثيلها الرمادي. الصور الرمادية تتكون حصريًا من درجات اللون الرمادي وتحمل معلومات الشدة فقط.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    dicomImage.Grayscale();
    dicomImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


