---
title: "CdrImagePage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CdrImagePage. تخزن البيانات وتضمن عدم تحميل بيانات إضافية من DataStreamContainer الأساسي"
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

تخزن البيانات وتضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/).

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

* class [CdrImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage/)
* assembly [Aspose.Imaging](../../../)


