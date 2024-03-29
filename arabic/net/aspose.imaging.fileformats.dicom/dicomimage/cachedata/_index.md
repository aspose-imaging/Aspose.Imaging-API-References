---
title: CacheData
second_title: Aspose.Imaging لمرجع NET API
description: تخزين البيانات الخاصة.
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/cachedata/
---
## DicomImage.CacheData method

تخزين البيانات الخاصة.

```csharp
public override void CacheData()
```

### أمثلة

يوضح المثال التالي كيفية تخزين جميع صفحات صورة DICOM مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف DICOM.
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // يخزن هذا الاستدعاء جميع الصفحات مؤقتًا بحيث لا يتم إجراء تحميل بيانات إضافي من دفق البيانات الأساسي.
    image.CacheData();

    // أو يمكنك تخزين الصفحات كل على حدة.
    foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage page in image.DicomPages)
    {
        page.CacheData();
    }
}
```

### أنظر أيضا

* class [DicomImage](../../dicomimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
