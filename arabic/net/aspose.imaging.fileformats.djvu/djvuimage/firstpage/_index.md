---
title: "DjvuImage.FirstPage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية DjvuImage. الوصول إلى الصفحة الأولى من مستند DjVu الخاص بك باستخدام هذه الخاصية. استرجع الصفحة الأولية بسرعة لبدء عرض أو معالجة مستندك بكفاءة"
type: docs
weight: 60
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/firstpage/
---
## DjvuImage.FirstPage property

الوصول إلى الصفحة الأولى من مستند DjVu الخاص بك باستخدام هذه الخاصية. استرجع بسرعة الصفحة الأولية لبدء عرض أو معالجة المستند بفعالية.

```csharp
public DjvuPage FirstPage { get; }
```

### Property Value

الصفحة الأولى.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | لا يمكن العثور على الصفحة الأولى |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DJVU من تدفق ملف وطباعة معلومات حول الصفحات.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

//قد يبدو الإخراج هكذا:
//الإجمالي الكلي للصفحات: 2
//رقم الصفحة النشطة:    1
//رقم الصفحة الأولى:     1
//رقم الصفحة الأخيرة:      2
//--------------------------------------------------
//رقم الصفحة:     1
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp، القنوات المستخدمة: 1
//--------------------------------------------------
//رقم الصفحة:     2
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp، القنوات المستخدمة: 1
```

### انظر أيضًا

* class [DjvuPage](../../djvupage/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


