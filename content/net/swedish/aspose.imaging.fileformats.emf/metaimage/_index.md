---
title: MetaImage
second_title: Aspose.Imaging för .NET API-referens
description: Basklass för metaobjektklasser
type: docs
weight: 6510
url: /sv/aspose.imaging.fileformats.emf/metaimage/
---
## MetaImage class

Basklass för metaobjektklasser

```csharp
public abstract class MetaImage : VectorImage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [Height](../../aspose.imaging/vectorimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Hämtar objektets höjd, i tum. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Hämtar eller sätter rekord. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Hämtar objektstorleken, i tum. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| override [Width](../../aspose.imaging/vectorimage/width) { get; } | Hämtar bildens bredd. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Hämtar objektets bredd, i tum. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop)(Rectangle) | Beskär den angivna rektangeln. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop_1)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Hämtar de inbäddade bilderna. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Returnerar listan över teckensnitt som används i metafilen men som inte hittades. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| abstract [GetUsedFonts](../../aspose.imaging.fileformats.emf/metaimage/getusedfonts)() | Returnerar listan över teckensnitt som används i metafilen. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ResizeType) | Ändrar storlek på bilden. |
| abstract [ResizeCanvas](../../aspose.imaging.fileformats.emf/metaimage/resizecanvas)(Rectangle) | Ändrar storleken på duken. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.imaging/image/save)() | Sparar bilddata till den underliggande strömmen. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Sparar objektets data till den angivna strömmen. |
| override [Save](../../aspose.imaging/image/save)(string) | Sparar bilden till den angivna filplatsen. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |

### Se även

* class [VectorImage](../../aspose.imaging/vectorimage)
* namnutrymme [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
