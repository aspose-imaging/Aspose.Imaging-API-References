---
title: PsdOptions
second_title: Aspose.Imaging för .NET API-referens
description: Skapa alternativ för psd-filformatet.
type: docs
weight: 10140
url: /sv/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Skapa alternativ för psd-filformatet.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Initierar en ny instans av[`PsdOptions`](../psdoptions) class. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Initierar en ny instans av[`PsdOptions`](../psdoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Hämtar eller ställer in antalet bitar per färgkanal. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Hämtar eller ställer in antalet färgkanaler. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Hämtar eller ställer in psd-färgläget. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Hämtar eller ställer in psd-komprimeringsmetoden. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Hämtar eller ställer in filformatsversionen. Det kan vara PSD eller PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Hämtar eller ställer in ett värde som anger om [uppdatera bildförhandsgranskningsdata] – alternativ som används för att maximera kompatibiliteten med andra PSD-bildvisare. Observera att textlager som ritar till slutlig layout inte stöds för Compact Framework platform |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Hämtar eller ställer in ett värde som indikerar om - Ta bort den globala textmotorresursen - Används för vissa psd-filer med textlager, endast i fallet när de inte kan öppnas i Adobe Photoshop efter bearbetning (mest för textlager som saknas teckensnitt). Efter att ha använt det här alternativet måste användaren göra nästa i öppnad i Photoshop-fil: Meny "Text" -&gt; "Bearbeta frånvarande teckensnitt". Efter den operationen kommer all text att visas igen. Observera att denna operation kan orsaka några slutliga layoutändringar. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Hämtar eller ställer in PSD-vektoriseringsalternativen. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Hämtar eller ställer in psd-filversionen. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | Hämta eller ställ in XMP-databehållare |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar användningen av Aspsoe.Imaging för .Net API för att konvertera bilder till PSD-format. För att uppnå detta mål laddar detta exempel en befintlig bild och sparar den sedan tillbaka till PSD-format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Skapar en instans av bildklass och initierar den med en befintlig fil via filsökväg
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Skapa en instans av klassen PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Ställ in CompressionMethod som RLE
    //Obs: Annan CompressionMethod som stöds är CompressionMethod.RAW [Ingen komprimering]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //Ställ in ColorMode på gråskala
    //Obs: Andra färglägen som stöds är ColorModes.Bitmap och ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Spara bilden på diskplatsen med medföljande PsdOptions-inställningar
    image.Save(dir + "output.psd", psdOptions);
}
```

Följande exempel visar hur man konverterar en flersidig vektorbild till PSD-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som lager i utdata-PSD:n.
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
