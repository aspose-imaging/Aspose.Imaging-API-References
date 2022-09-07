---
title: WebPOptions
second_title: Aspose.Imaging för .NET API-referens
description: Webp bildalternativ
type: docs
weight: 10280
url: /sv/net/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

Webp bildalternativ

```csharp
public class WebPOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WebPOptions](webpoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor) { get; set; } | Hämtar eller ställer in färgen på den animerade bakgrunden. |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount) { get; set; } | Hämtar eller ställer in animationsslingantalet. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`WebPOptions`](../webpoptions) är förlustfri. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality) { get; set; } | Hämtar eller ställer in kvaliteten. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar hur man skapar en WebP-bild från en annan rasterbild med annan komprimeringskvalitet.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en GIF-animation
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // för förlustfri komprimering, ökad kvalitetsinställning ökar komprimeringskvaliteten och minskar filstorleken
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // filstorlek: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // filstorlek: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // filstorlek: 40 KB


    // för komprimering med förlust, ökar kvalitetsvärdet bildkvaliteten och filstorleken
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // filstorlek: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // filstorlek: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // filstorlek: 51 KB
}
```

Följande exempel visar hur man konverterar en flersidig vektorbild till WEBP-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som animerade ramar i utdata-WEBP.
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
