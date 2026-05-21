---
title: "DicomImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. تقوم هذه الطريقة بتخزين البيانات بفعالية، مما يحسن الأداء ويضمن وصولًا سريعًا عند الحاجة. مثالية للمطورين الذين يسعون لتعزيز سرعة وكفاءة تطبيقاتهم من خلال إدارة موارد البيانات بذكاء."
type: docs
weight: 170
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/cachedata/
---
## DicomImage.CacheData method

تقوم هذه الطريقة بتخزين البيانات مؤقتًا بكفاءة، مما يحسن الأداء ويضمن وصولًا سريعًا عند الحاجة. مثالي للمطورين الذين يرغبون في تعزيز سرعة وكفاءة تطبيقاتهم من خلال إدارة موارد البيانات بذكاء.

```csharp
public override void CacheData()
```

## أمثلة

المثال التالي يوضح كيفية تخزين جميع صفحات صورة DICOM.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة من ملف DICOM.
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // هذه العملية تخزن جميع الصفحات بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    image.CacheData();

    // أو يمكنك تخزين الصفحات بشكل فردي.
    foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage page in image.DicomPages)
    {
        page.CacheData();
    }
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


