---
title: "DjvuImage.Pages"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية DjvuImage. وصول إلى الصفحات الفردية لمجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. سهل التنقل والتعامل مع مستندك أو كتابك المخزن بصيغة DjVu من خلال الوصول إلى كل صفحة مباشرة. حسّن كفاءة سير العمل لديك مع استرجاع الصفحات بسهولة."
type: docs
weight: 120
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/pages/
---
## DjvuImage.Pages property

الوصول إلى الصفحات الفردية في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. بسط التنقل والتعامل مع مستندك أو كتابك المخزن بتنسيق DjVu عبر الوصول المباشر إلى كل صفحة. حسّن كفاءة سير العمل باسترجاع الصفحات بسهولة.

```csharp
public override Image[] Pages { get; }
```

### Property Value

الصفحات.

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DJVU من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // احفظ كل صفحة كصورة PNG منفردة.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // أنشئ اسم ملف استنادًا إلى رقم الصفحة.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [Image](../../../aspose.imaging/image/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


