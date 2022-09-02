---
title: EpsInterchangeImage
second_title: Aspose.Imaging för .NET API-referens
description: Klass för Encapsulated PostScript Interchange format
type: docs
weight: 6570
url: /sv/net/aspose.imaging.fileformats.eps/epsinterchangeimage/
---
## EpsInterchangeImage class

Klass för Encapsulated PostScript Interchange format

```csharp
public class EpsInterchangeImage : EpsImage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Hämtar begränsningsrutan längst ner till vänster position |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | Hämtar BoundingBox-strängen value |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Hämtar begränsningsrutan uppe till höger position |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Hämtar fältet CreationDate |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | Får han CreationDate field string value |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Hämtar Skaparfältet |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| override [EpsType](../../aspose.imaging.fileformats.eps/epsinterchangeimage/epstype) { get; } | Får EPS subtyp value |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/hasrasterpreview) { get; } | Får ett värde som indikerar om denna instans har formatspecifik raster preview |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Hämtar objektets höjd, i tum. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Hämtar sidnumret |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Får sidorna count |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Får Photoshop-förhandsvisningsminiatyr (om den finns i initial EPS-data) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Hämtar PostScript-versionsfältet |
| [PreviewHeight](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewheight) { get; } | Hämtar höjden på förhandsgranskningsbilden |
| [PreviewWidth](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewwidth) { get; } | Hämtar bredden på förhandsgranskningsbilden |
| [RasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/rasterpreview) { get; } | Får svart/vit rasterförhandsgranskning (om sådan finns) eller null |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Hämtar objektstorleken, i tum. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Hämtar titelfältet |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Hämtar bildens bredd. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Hämtar objektets bredd, i tum. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Cache kan inte användas. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [ConvertToBinary](../../aspose.imaging.fileformats.eps/epsinterchangeimage/converttobinary)() | Konverterar denna instans till[`EpsBinaryImage`](../epsbinaryimage) |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Hämtar de inbäddade bilderna. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.imaging/image/save)() | Sparar bilddata till den underliggande strömmen. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Sparar objektets data till den angivna strömmen. |
| override [Save](../../aspose.imaging/image/save)(string) | Sparar bilden till den angivna filplatsen. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |
| [explicit operator](../../aspose.imaging.fileformats.eps/epsinterchangeimage/op_explicit) | Utför en explicit konvertering från[`EpsBinaryImage`](../epsbinaryimage) till[`EpsInterchangeImage`](../epsinterchangeimage) |

### Se även

* class [EpsImage](../epsimage)
* namnutrymme [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
