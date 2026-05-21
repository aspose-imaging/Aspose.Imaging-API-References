---
title: "DicomImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. حسّن إضاءة الصورة من خلال تعديل السطوع باستخدام طريقة معلمة تسمح للمطورين بضبط سطوع الصور بدقة. هذه الدالة سهلة الاستخدام تمكّن المطورين من تعديل سطوع الصورة بسلاسة، مقدمة مرونة وتحكمًا في الجماليات البصرية."
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/
---
## DicomImage.AdjustBrightness method

حسّن إضاءة الصورة من خلال تعديل *السطوع*، وهي طريقة معلمة تسمح للمطورين بضبط إضاءة الصور بدقة. تمكّن هذه الدالة سهلة الاستخدام المطورين من تعديل سطوع الصورة بسلاسة، مقدمةً مرونة وتحكمًا في الجماليات البصرية.

```csharp
public override void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يقوم بتصحيح سطوع صورة DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    dicomImage.AdjustBrightness(50);
    dicomImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


