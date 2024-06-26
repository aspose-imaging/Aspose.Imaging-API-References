---
title: VectorRasterizationOptions.Positioning
second_title: Aspose.Imaging for .NET API Reference
description: VectorRasterizationOptions property. Gets or sets the positioning
type: docs
weight: 100
url: /net/aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/
---
## VectorRasterizationOptions.Positioning property

Gets or sets the positioning.

```csharp
public PositioningTypes Positioning { get; set; }
```

### Property Value

The positioning.

## Examples

The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// Setting a memory limit of 10 megabytes for a target loaded image.
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

The following example shows how to export all pages of CDR document to PDF.

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

### See Also

* enum [PositioningTypes](../../positioningtypes/)
* class [VectorRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


