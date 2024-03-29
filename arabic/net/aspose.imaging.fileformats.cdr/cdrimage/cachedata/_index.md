---
title: CacheData
second_title: Aspose.Imaging لمرجع NET API
description: يخزن البيانات مؤقتًا ويضمن عدم إجراء تحميل بيانات إضافي من الملف الأساسي DataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimage/cachedata/
---
## CdrImage.CacheData method

يخزن البيانات مؤقتًا ويضمن عدم إجراء تحميل بيانات إضافي من الملف الأساسي [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

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

* class [CdrImage](../../cdrimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Cdr](../../cdrimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
