---
title: "VectorRasterizationOptions.Positioning"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية VectorRasterizationOptions. يحصل أو يضبط التموضع"
type: docs
weight: 100
url: /ar/net/aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/
---
## VectorRasterizationOptions.Positioning property

الحصول أو تعيين التموضع.

```csharp
public PositioningTypes Positioning { get; set; }
```

### Property Value

التموضع.

## أمثلة

المثال التالي يوضح كيفية تعيين حد الذاكرة عند تحميل صورة CMX. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// تعيين حد الذاكرة إلى 10 ميغابايت للصورة المحملة المستهدفة.
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

المثال التالي يوضح كيفية تصدير جميع صفحات مستند CDR إلى PDF.

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

### انظر أيضًا

* enum [PositioningTypes](../../positioningtypes/)
* class [VectorRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


