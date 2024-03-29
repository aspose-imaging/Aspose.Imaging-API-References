---
title: Positioning
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على تحديد المواقع أو تعيينه.
type: docs
weight: 100
url: /ar/net/aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/
---
## VectorRasterizationOptions.Positioning property

الحصول على تحديد المواقع أو تعيينه.

```csharp
public PositioningTypes Positioning { get; set; }
```

### Property_Value

تحديد المواقع .

### أمثلة

يوضح المثال التالي كيفية تعيين حد للذاكرة عند تحميل صورة CMX. حد الذاكرة هو الحد الأقصى للحجم المسموح به (بالميغابايت) لجميع المخازن المؤقتة الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// تعيين حد ذاكرة 10 ميغا بايت لصورة محملة الهدف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

يوضح المثال التالي كيفية تصدير كل صفحات مستند CDR إلى PDF.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3570";
string inputCdrFileName = System.IO.Path.Combine(dir, "tiger.cdr");
string outputPdfFileName = System.IO.Path.Combine(dir, "tiger.cdr.pdf");

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputCdrFileName))
{
    Aspose.Imaging.ImageOptions.PdfOptions pdfOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    Aspose.Imaging.ImageOptions.CdrRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.CdrRasterizationOptions
    {
        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
        SmoothingMode = Aspose.Imaging.SmoothingMode.None,
        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
    };

    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    image.Save(outputPdfFileName, pdfOptions);
}
```

### أنظر أيضا

* enum [PositioningTypes](../../positioningtypes)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
