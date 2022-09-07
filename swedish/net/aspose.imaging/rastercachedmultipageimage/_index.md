---
title: RasterCachedMultipageImage
second_title: Aspose.Imaging för .NET API-referens
description: Rasterbilden med flera sidor
type: docs
weight: 10800
url: /sv/net/aspose.imaging/rastercachedmultipageimage/
---
## RasterCachedMultipageImage class

Rasterbilden med flera sidor

```csharp
public abstract class RasterCachedMultipageImage : RasterCachedImage, IMultipageImage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Får värdet filformat |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Får ett värde som indikerar om denna instans har alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Får ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Får opacitet för denna bild. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| abstract [PageCount](../../aspose.imaging/rastercachedmultipageimage/pagecount) { get; } | Hämtar sidantal. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Hämtar eller ställer in sidexporteringsåtgärden. Observera att inställning av den här metoden automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas. |
| abstract [Pages](../../aspose.imaging/rastercachedmultipageimage/pages) { get; } | Hämtar sidorna. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Hämtar den rå radstorleken i byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Får bilden genomskinlig färg. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Hämtar bildens bredd. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-data från frame. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedmultipageimage/adjustbrightness)(int) | Justering av en*brightness* för bild. |
| override [AdjustContrast](../../aspose.imaging/rastercachedmultipageimage/adjustcontrast)(float) | [`Image`](../image) kontrasterande |
| override [AdjustGamma](../../aspose.imaging/rastercachedmultipageimage/adjustgamma#adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.imaging/rastercachedmultipageimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley#binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley#binarizebradley_1)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeFixed](../../aspose.imaging/rastercachedmultipageimage/binarizefixed)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedmultipageimage/binarizeotsu)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Cachelagrar data privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop#crop)(Rectangle) | Beskär bilden. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop#crop_1)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.imaging/rastercachedmultipageimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| override [Filter](../../aspose.imaging/rastercachedmultipageimage/filter)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../image/save) metod som den andra parametern. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Får en bildpixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Hämtar skevningsvinkeln. Denna metod är tillämplig på skannade textdokument, för att bestämma snedställningsvinkeln vid skanning. |
| override [Grayscale](../../aspose.imaging/rastercachedmultipageimage/grayscale)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Laddar 32-bitars ARGB-pixlar. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Laddar 64-bitars ARGB-pixlar. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB-pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../rasterimage/getskewangle) och[`Rotate`](../rasterimage/rotate) metoder. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle#normalizeangle_1)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder!:GetSkewAngle och[`Rotate`](./rotate) metoder. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor#replacecolor_1)(int, byte, int) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging/rastercachedmultipageimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging/rastercachedmultipageimage/resize#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.imaging/rastercachedmultipageimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate bild runt mitten. |
| override [RotateFlip](../../aspose.imaging/rastercachedmultipageimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder alla sidor. |
| [Save](../../aspose.imaging/image/save)() | Sparar bilddata till den underliggande strömmen. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Sparar objektets data till den angivna strömmen. |
| override [Save](../../aspose.imaging/image/save)(string) | Sparar bilden till den angivna filplatsen. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Sparar 32-bitars ARGB-pixlar. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Sparar pixlarna. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Sparar pixlarna. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Sparar rådata. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Ställer in en 32-bitars ARGB-pixel för den angivna positionen. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konverterar rasterbilden till bitmappen. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Se även

* class [RasterCachedImage](../rastercachedimage)
* interface [IMultipageImage](../imultipageimage)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
