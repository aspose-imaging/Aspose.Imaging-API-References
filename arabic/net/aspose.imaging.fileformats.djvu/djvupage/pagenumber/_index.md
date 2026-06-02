---
title: "DjvuPage.PageNumber"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية DjvuPage. تسترجع رقم الصفحة"
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.djvu/djvupage/pagenumber/
---
## DjvuPage.PageNumber property

يحصل على رقم الصفحة.

```csharp
public int PageNumber { get; }
```

### Property Value

رقم الصفحة.

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

* class [DjvuPage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvupage/)
* assembly [Aspose.Imaging](../../../)


