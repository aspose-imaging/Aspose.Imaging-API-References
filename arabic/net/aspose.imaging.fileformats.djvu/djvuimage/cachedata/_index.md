---
title: "DjvuImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. خزن البيانات مؤقتًا بشكل خاص لتحسين الأداء وتقليل الحاجة إلى استرجاع البيانات المتكرر من المصادر الخارجية. يساعد هذا النهج أيضًا في حفظ الموارد، خاصةً في السيناريوهات التي يكون فيها الوصول إلى البيانات متكررًا أو الموارد محدودة."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/cachedata/
---
## DjvuImage.CacheData method

قم بتخزين البيانات مؤقتًا بشكل خاص لتحسين الأداء وتقليل الحاجة إلى استرجاع البيانات المتكرر من المصادر الخارجية. يساعد هذا النهج أيضًا في الحفاظ على الموارد، خاصةً في السيناريوهات التي يكون فيها الوصول إلى البيانات متكررًا أو الموارد محدودة.

```csharp
public override void CacheData()
```

## أمثلة

المثال التالي يوضح كيفية تخزين جميع صفحات صورة DJVU مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة من ملف DJVU.
using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // هذه العملية تخزن جميع الصفحات بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    image.CacheData();

    // أو يمكنك تخزين الصفحات بشكل فردي.
    foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


