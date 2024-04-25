---
title: GifImage
second_title: Aspose.Imaging för .NET API-referens
description: En gif-bild.
type: docs
weight: 6700
url: /sv/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

En gif-bild.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | Initierar en ny instans av[`GifImage`](../gifimage) class. |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | Initierar en ny instans av[`GifImage`](../gifimage) class. |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Initierar en ny instans av[`GifImage`](../gifimage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Hämtar eller ställer in den aktiva ramen. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Hämtar eller ställer in bakgrundsfärgen. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Hämtar eller ställer in bakgrundsfärgindex. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Hämtar GIF-blocken. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Får värdet filformat |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Får ett värde som indikerar om denna instans har alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Får ett värde som indikerar om bilden har bakgrundsfärg. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Hämtar eller ställer in ett värde som anger om GIF har trailer. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Får ett värde som indikerar om den aktiva ramen har transparent färg. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Får opacitet för denna bild (aktiv ram). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Får ett värde som indikerar om denna bildinstans är sammanflätad. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten är sorterad. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Får antalet loopar (om gif-bilden innehåller information om loopar) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Hämtar sidantal. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Hämtar eller ställer in sidexporteringsåtgärden. Observera att inställning av den här metoden automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Hämtar sidorna. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Hämtar eller ställer in palettens färgupplösningsbitar. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Hämtar eller ställer in pixelns bildförhållande. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Hämtar den rå radstorleken i byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Får aktiv ram transparent färg. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Hämtar bildens bredd. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Lägger till ett nytt GIF-block. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Lägger till sida i bilden. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Justering av en*brightness* för bild. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Justerar kontrasten. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Cachelagrar data privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Rensar alla GIF-block. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | Beskär bilden. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Får en bildpixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Hämtar skevningsvinkeln. Denna metod är tillämplig på skannade textdokument, för att bestämma snedställningsvinkeln vid skanning. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Transformation av en bild till dess gråskalerepresentation |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Lägger till ett nytt GIF-block. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Laddar 32-bitars ARGB-pixlar. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Laddar 64-bitars ARGB-pixlar. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB-pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) och[`Rotate`](../../aspose.imaging/rasterimage/rotate) metoder. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder!:GetSkewAngle och[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) metoder. |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Beställer GIF-blocken enligt GIF-specifikationen. Några[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) kan tas bort för korrekt GIF-layout. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Tar bort GIF-blocket. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Ändrar storleken på bilden med hjälp av helbild för varje GIF-sida. Krävs för att undvika eventuella artefakter. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Utför proportionell storleksändring på bilden. Den proportionella storleksändringen kommer att ändra storlek på varje bildruta enligt förhållandet mellan*newWidth*/bredd och*newHeight* /höjd. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate bild runt mitten. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder endast den aktiva ramen. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Ställer in alla bildrutors varaktighet i millisekunder. Ändring av detta värde återställer fördröjningen för alla bildrutor. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konverterar rasterbilden till bitmappen. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Exempel

Export av en del av animationen från GIF-bild baserat på tidsintervall.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

Det här exemplet visar hur man skapar en GIF-bild och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa ett GIF-ramblock på 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fyll hela blocket med rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Skapa flersidig GIF-bild med ensidiga rasterbilder.

```csharp
[C#]

static void Main(string[] args)
{
    // Ladda ramar
    var frames = LoadFrames("Animation frames").ToArray();

    // Skapa GIF-bild med den första bildrutan
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Lägg till ramar till GIF-bilden med AddPage-metoden
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Spara GIF-bild
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Se även

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
