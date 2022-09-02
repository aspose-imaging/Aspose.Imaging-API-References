---
title: OtgImage
second_title: Aspose.Imaging för .NET API-referens
description: Otg-bilden
type: docs
weight: 7400
url: /sv/net/aspose.imaging.fileformats.opendocument/otgimage/
---
## OtgImage class

Otg-bilden

```csharp
public class OtgImage : OdImage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [OtgImage](otgimage#constructor)(StreamContainer) | Initierar en ny instans av[`OtgImage`](../otgimage) class. |
| [OtgImage](otgimage#constructor_1)(StreamContainer, LoadOptions) | Initierar en ny instans av[`OtgImage`](../otgimage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/otgimage/fileformat) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [Height](../../aspose.imaging.fileformats.opendocument/odimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Hämtar objektets höjd, i tum. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata) { get; } | Hämtar metadata. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount) { get; } | Hämtar sidantal. |
| override [PageExportingAction](../../aspose.imaging.fileformats.opendocument/otgimage/pageexportingaction) { get; set; } | Hämtar eller ställer in sidexporteringsåtgärden. Observera att inställning av den här metoden automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas. |
| override [Pages](../../aspose.imaging.fileformats.opendocument/otgimage/pages) { get; } | Hämtar sidorna. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records) { get; } | Hämtar posterna. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Hämtar objektstorleken, i tum. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| override [Width](../../aspose.imaging.fileformats.opendocument/odimage/width) { get; } | Hämtar bildens bredd. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Hämtar objektets bredd, i tum. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.opendocument/otgimage/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Hämtar de inbäddade bilderna. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| override [RotateFlip](../../aspose.imaging.fileformats.opendocument/odimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.imaging/image/save)() | Sparar bilddata till den underliggande strömmen. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Sparar objektets data till den angivna strömmen. |
| override [Save](../../aspose.imaging/image/save)(string) | Sparar bilden till den angivna filplatsen. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |

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

* class [OdImage](../odimage)
* namnutrymme [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
