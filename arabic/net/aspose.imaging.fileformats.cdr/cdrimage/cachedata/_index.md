---
title: "CdrImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CdrImage. خزن البيانات مؤقتًا بسهولة لمنع التحميل الإضافي من المصدر الأساسي باستخدام هذه الطريقة سهلة الاستخدام. مثالي للمطورين الذين يسعون لتحسين الأداء عن طريق تحميل البيانات مسبقًا لضمان وصول أسرع وتشغيل أكثر سلاسة في تطبيقاتهم. DataStreamContainer"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimage/cachedata/
---
## CdrImage.CacheData method

خزن البيانات بسهولة لمنع التحميل الإضافي من المصدر الأساسي باستخدام هذه الطريقة الصديقة للمستخدم. مثالي للمطورين الذين يسعون لتحسين الأداء عن طريق تحميل البيانات مسبقًا، لضمان وصول أسرع وتشغيل أكثر سلاسة في تطبيقاتهم. [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/).

```csharp
public override void CacheData()
```

## أمثلة

يوضح المثال التالي كيفية تخزين جميع صفحات صورة CDR مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة من ملف CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // هذه العملية تخزن الصفحة الافتراضية فقط مؤقتًا.
    image.CacheData();

    // قم بتخزين جميع الصفحات مؤقتًا بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### انظر أيضًا

* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


