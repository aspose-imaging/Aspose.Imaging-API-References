---
title: "MultiPageOptions.PageTitles"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية MultiPageOptions. تحصل أو تعين عناوين الصفحات"
type: docs
weight: 80
url: /ar/net/aspose.imaging.imageoptions/multipageoptions/pagetitles/
---
## MultiPageOptions.PageTitles property

الحصول أو تعيين عناوين الصفحات.

```csharp
public string[] PageTitles { get; set; }
```

### Property Value

عناوين الصفحات.

## أمثلة

يوضح هذا المثال كيفية تحويل صورة DJVU متعددة الصفحات إلى صورة TIFF متعددة الإطارات.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // لاحظ أنه إذا كانت الصورة ملونة، فسيتم تحويلها تلقائيًا إلى صيغة أبيض/أسود وفقًا للخيار أدناه:
        saveOptions.BitsPerSample = new ushort[] { 1 };

        saveOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.DjvuMultiPageOptions();

        // بشكل افتراضي، سيتم تخزين جميع الصفحات في ملف TIFF الناتج، ولكن يمكن تحديد مجموعة الصفحات المطلوبة صراحةً.
        // سيتم تصدير الصفحة الأولى والثانية فقط.
        saveOptions.MultiPageOptions.Pages = new int[] { 0, 1 };

        // عيّن عناوين الصفحات.
        saveOptions.MultiPageOptions.PageTitles = new string[] { "The First Page", "The Second Page" };

        // احفظ إلى TIFF
        djvuImage.Save(dir + "sample.tif", saveOptions);
    }
}
```

### انظر أيضًا

* class [MultiPageOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../multipageoptions/)
* assembly [Aspose.Imaging](../../../)


