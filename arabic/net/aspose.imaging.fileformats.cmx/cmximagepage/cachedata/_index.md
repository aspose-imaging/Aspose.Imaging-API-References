---
title: "CmxImagePage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "CmxImagePage طريقة. لا يمكن استخدام الذاكرة المؤقتة"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.cmx/cmximagepage/cachedata/
---
## CmxImagePage.CacheData method

لا يمكن استخدام الذاكرة المؤقتة.

```csharp
public override void CacheData()
```

## أمثلة

المثال التالي يوضح كيفية تخزين جميع صفحات صورة CMX مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة من ملف CMX.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // هذه العملية تخزن الصفحة الافتراضية فقط مؤقتًا.
    image.CacheData();

    // قم بتخزين جميع الصفحات مؤقتًا بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### انظر أيضًا

* class [CmxImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximagepage/)
* assembly [Aspose.Imaging](../../../)


