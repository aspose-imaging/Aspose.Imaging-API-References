---
title: "CdrImage.Pages"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية CdrImage. استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى صفحات فردية داخل صور متعددة الصفحات ومعالجتها لضمان تنقل ومعالجة فعّالة"
type: docs
weight: 80
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimage/pages/
---
## CdrImage.Pages property

استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يسعون للوصول إلى صفحات فردية داخل الصور متعددة الصفحات ومعالجتها، مما يضمن تنقلًا فعالًا ومعالجةً كفء.

```csharp
public override Image[] Pages { get; }
```

### Property Value

الصفحات.

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

المثال التالي يوضح كيفية تصدير صفحة واحدة من مستند CDR إلى PDF.

```csharp
[C#]

int pageNumber = 0;
string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3570";
string inputCdrFileName = System.IO.Path.Combine(dir, "tiger.cdr");
string outputPdfFileName = System.IO.Path.Combine(dir, "tiger.cdr.page" + pageNumber + ".pdf");

using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage) Aspose.Imaging.Image.Load(inputCdrFileName))
{
    Aspose.Imaging.FileFormats.Cdr.CdrImagePage imagePage = (Aspose.Imaging.FileFormats.Cdr.CdrImagePage) image.Pages[pageNumber];

    Aspose.Imaging.ImageOptions.PdfOptions pdfOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    Aspose.Imaging.ImageOptions.CdrRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.CdrRasterizationOptions()
    {
        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
        SmoothingMode = Aspose.Imaging.SmoothingMode.None
    };

    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    pdfOptions.VectorRasterizationOptions.PageWidth = imagePage.Width;
    pdfOptions.VectorRasterizationOptions.PageHeight = imagePage.Height;

    imagePage.Save(outputPdfFileName, pdfOptions);
}
```

### انظر أيضًا

* class [Image](../../../aspose.imaging/image/)
* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


