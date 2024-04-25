---
title: Jpeg2000Options
second_title: Aspose.Imaging för .NET API-referens
description: Filformatsalternativen Jpeg2000.
type: docs
weight: 10020
url: /sv/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Filformatsalternativen Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Initierar en ny instans av[`Jpeg2000Options`](../jpeg2000options) class. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Initierar en ny instans av[`Jpeg2000Options`](../jpeg2000options) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | Hämtar eller ställer in JPEG2000 codec |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Hämtar eller ställer in Jpeg-kommentarmarkörerna. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Hämtar eller ställer in matrisen av kompressionsförhållande. Olika kompressionsförhållanden för på varandra följande lager. Hastigheten som anges för varje kvalitetsnivå är den önskade kompressionsfaktorn. Minskande förhållanden krävs. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Hämtar eller ställer in ett värde som indikerar om du använder den irreversibla DWT 9-7 (true) eller om du använder förlustfri DWT 5-3-komprimering (standard). |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Följande exempel visar hur man konverterar en flersidig vektorbild till JPEG 2000-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna. Faktum är att bara en sida kommer att rastreras eftersom JPEG 2000 inte är ett flersidigt format.
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
