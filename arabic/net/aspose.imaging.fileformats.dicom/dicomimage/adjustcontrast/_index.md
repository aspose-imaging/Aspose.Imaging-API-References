---
title: "DicomImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. حسّن تباين الصورة باستخدام هذه الطريقة سهلة الاستخدام التي تعدل الفارق بين المناطق الفاتحة والداكنة. حسّن الوضوح البصري والتعريف بسهولة، موفرة للمطورين تحكمًا بديهيًا في تباين الصورة لتحقيق عرض مثالي."
type: docs
weight: 120
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/
---
## DicomImage.AdjustContrast method

حسّن تباين [`Image`](../../../aspose.imaging/image/) باستخدام هذه الطريقة سهلة الاستخدام، التي تعدل الفارق بين المناطق الفاتحة والداكنة. حسّن الوضوح البصري والتعريف بسهولة، موفرة للمطورين تحكمًا بديهيًا في تباين الصورة لتحقيق عرض مثالي.

```csharp
public override void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

## أمثلة

المثال التالي يقوم بتصحيح تباين صورة DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    dicomImage.AdjustContrast(50f);
    dicomImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


