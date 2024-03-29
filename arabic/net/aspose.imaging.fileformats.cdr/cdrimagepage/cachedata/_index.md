---
title: CacheData
second_title: Aspose.Imaging لمرجع NET API
description: يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساسDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### أمثلة

يوضح المثال التالي كيفية تخزين جميع صفحات صورة CDR مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // يخزن هذا الاستدعاء مؤقتًا الصفحة الافتراضية فقط.
    image.CacheData();

    // تخزين جميع الصفحات مؤقتًا بحيث لا يتم إجراء أي تحميل بيانات إضافية من دفق البيانات الأساسي.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### أنظر أيضا

* class [CdrImagePage](../../cdrimagepage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
