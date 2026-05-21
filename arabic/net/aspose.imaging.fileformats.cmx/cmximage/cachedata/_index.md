---
title: "CmxImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CmxImage. خزن البيانات مؤقتاً لمنع تحميل إضافي من المصدر الأساسي DataStreamContainer باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يسعون لتحسين الأداء عبر تحميل البيانات مسبقاً لضمان وصول أسرع وعمل أكثر سلاسة في تطبيقاتهم."
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.cmx/cmximage/cachedata/
---
## CmxImage.CacheData method

خزن البيانات لمنع تحميل إضافي من المصدر الأساسي [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يسعون لتحسين الأداء عبر تحميل البيانات مسبقاً، وضمان وصول أسرع وعمل أكثر سلاسة في تطبيقاتهم.

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

* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


