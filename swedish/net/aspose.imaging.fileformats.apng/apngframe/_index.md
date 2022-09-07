---
title: ApngFrame
second_title: Aspose.Imaging för .NET API-referens
description: Den animerade PNG-bildramen
type: docs
weight: 1310
url: /sv/net/aspose.imaging.fileformats.apng/apngframe/
---
## ApngFrame class

Den animerade PNG-bildramen

```csharp
public class ApngFrame : RasterCachedImage, IAnimationFrame
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| override [BackgroundColor](../../aspose.imaging.fileformats.apng/apngframe/backgroundcolor) { get; set; } | Får bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.apng/apngframe/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [DisposalMethod](../../aspose.imaging.fileformats.apng/apngframe/disposalmethod) { get; } | Hämtar bortskaffningsmetoden. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Får värdet filformat |
| [FrameLeft](../../aspose.imaging.fileformats.apng/apngframe/frameleft) { get; } | Får ramen vänster offset. |
| [FrameTime](../../aspose.imaging.fileformats.apng/apngframe/frametime) { get; set; } | Hämtar eller ställer in bildrutelängden. |
| [FrameTop](../../aspose.imaging.fileformats.apng/apngframe/frametop) { get; } | Får ramens toppförskjutning. |
| override [HasAlpha](../../aspose.imaging.fileformats.apng/apngframe/hasalpha) { get; } | Få ett värde som anger om denna instans har alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.apng/apngframe/hasbackgroundcolor) { get; set; } | Får ett värde som anger om har bakgrundsfärg. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.apng/apngframe/hastransparentcolor) { get; set; } | Får ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.imaging.fileformats.apng/apngframe/height) { get; } | Hämtar bildhöjden. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Får opacitet för denna bild. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Hämtar den rå radstorleken i byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| override [TransparentColor](../../aspose.imaging.fileformats.apng/apngframe/transparentcolor) { get; set; } | Får den genomskinliga färgen. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.apng/apngframe/width) { get; } | Hämtar bildens bredd. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Justera en ljusstyrka för bilden. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Bild kontrasterande |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.imaging.fileformats.apng/apngframe/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | Beskär bilden. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| [GetFullFrame](../../aspose.imaging.fileformats.apng/apngframe/getfullframe)() | Får hela bilden. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Får en bildpixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Hämtar skevningsvinkeln. Denna metod är tillämplig på skannade textdokument, för att bestämma snedställningsvinkeln vid skanning. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Laddar 32-bitars ARGB-pixlar. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Laddar 64-bitars ARGB-pixlar. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB-pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) och[`Rotate`](../../aspose.imaging/rasterimage/rotate) metoder. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) och[`Rotate`](../../aspose.imaging/rasterimage/rotate) metoder. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | Rotera bilden runt mitten. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
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
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konverterar rasterbilden till bitmappen. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Exempel

Följande exempel visar hur man skapar APNG-bild från en annan rasterbild på en sida.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Det är möjligt att ställa in bildens standardbildtid där: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Rengöring eftersom bilden innehåller en ram som standard
        apngImage.RemoveAllFrames();

        // lägg till första bildrutan
        apngImage.AddFrame(sourceImage);

        // lägg till mellanliggande ramar
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // lägg till sista bildrutan
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Se även

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* interface [IAnimationFrame](../../aspose.imaging/ianimationframe)
* namnutrymme [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
