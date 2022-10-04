---
title: PdfOptions
second_title: Aspose.Imaging för .NET API-referens
description: PDF-alternativen.
type: docs
weight: 10110
url: /sv/net/aspose.imaging.imageoptions/pdfoptions/
---
## PdfOptions class

PDF-alternativen.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| [PageSize](../../aspose.imaging.imageoptions/pdfoptions/pagesize) { get; set; } | Hämtar eller ställer in storleken på sidan. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [PdfCoreOptions](../../aspose.imaging.imageoptions/pdfoptions/pdfcoreoptions) { get; set; } | PDF-kärnalternativen |
| [PdfDocumentInfo](../../aspose.imaging.imageoptions/pdfoptions/pdfdocumentinfo) { get; set; } | Hämtar eller ställer in metadata för dokument. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [UseOriginalImageResolution](../../aspose.imaging.imageoptions/pdfoptions/useoriginalimageresolution) { get; set; } | Hämtar eller ställer in ett värde som anger att originalbilden ska användas DPI resolution |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Följande exempel visar hur man konverterar en flersidig vektorbild till PDF-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.pdf");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PdfOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna till motsvarande sidor i det utgående PDF-dokumentet.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Se även

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->