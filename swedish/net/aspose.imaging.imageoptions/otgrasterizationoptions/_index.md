---
title: OtgRasterizationOptions
second_title: Aspose.Imaging för .NET API-referens
description: Otg-rastreringsalternativen
type: docs
weight: 10090
url: /sv/net/aspose.imaging.imageoptions/otgrasterizationoptions/
---
## OtgRasterizationOptions class

Otg-rastreringsalternativen

```csharp
public class OtgRasterizationOptions : OdRasterizationOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [OtgRasterizationOptions](otgrasterizationoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor) { get; set; } | Hämtar eller ställer in en bakgrundsfärg. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx) { get; set; } | Hämtar eller ställer in gränsen X. |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery) { get; set; } | Hämtar eller ställer in gränsen Y. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing) { get; set; } | Hämtar eller ställer in ett värde som anger om mittritning. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor) { get; set; } | Får eller ställer in en förgrundsfärg. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight) { get; set; } | Hämtar eller ställer in sidhöjden. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize) { get; set; } | Hämtar eller ställer in sidstorleken. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth) { get; set; } | Hämtar eller ställer in sidbredden. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning) { get; set; } | Får eller ställer in positioneringen. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode) { get; set; } | Hämtar eller ställer in utjämningsläget. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint) { get; set; } | Hämtar eller ställer in textåtergivningstipset. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto)(VectorRasterizationOptions) | Kopierar till. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Följande kodavsnitt visar hur man konverterar en OTG-bild till PDF och andra bildformat.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### Se även

* class [OdRasterizationOptions](../odrasterizationoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
