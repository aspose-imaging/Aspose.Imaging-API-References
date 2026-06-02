---
title: "CmxImage.Pages"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية CmxImage. استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى الصفحات الفردية داخل الصور متعددة الصفحات ومعالجة فعّالة."
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.cmx/cmximage/pages/
---
## CmxImage.Pages property

استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يسعون للوصول إلى صفحات فردية داخل الصور متعددة الصفحات ومعالجتها، مما يضمن تنقلًا فعالًا ومعالجةً كفء.

```csharp
public override Image[] Pages { get; }
```

### Property Value

الصفحات.

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

* class [Image](../../../aspose.imaging/image/)
* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


