---
title: ApngImage
second_title: Aspose.Imaging för .NET API-referens
description: Den animerade PNG-bilden.
type: docs
weight: 1320
url: /sv/net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

Den animerade PNG-bilden.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | Initierar en ny instans av[`ApngImage`](../apngimage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime) { get; set; } | Hämtar eller ställer in standardbildlängden. Används när du skapar nya ramar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat) { get; } | Får värdet filformat |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Får ett värde som indikerar om denna instans har alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Får ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Hämtar bildhöjden. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Får opacitet för denna bild. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced) { get; } | Får ett värde som indikerar om detta[`PngImage`](../../aspose.imaging.fileformats.png/pngimage) är sammanflätad. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays) { get; set; } | Hämtar eller ställer in antalet gånger för loop-animering. 0 indikerar oändlig looping. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount) { get; } | Hämtar sidantal. |
| override [PageExportingAction](../../aspose.imaging.fileformats.apng/apngimage/pageexportingaction) { get; set; } | Hämtar eller ställer in sidexporteringsåtgärden. Observera att inställning av den här metoden automatiskt frigör sidresurser efter att den har körts. Den kommer att köras precis innan varje sida sparas. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages) { get; } | Hämtar sidorna. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Hämtar bildens bredd. |
| override [XmpData](../../aspose.imaging.fileformats.apng/apngimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe)() | Lägger till en ny ram i slutet av den egna ramsamlingen. En ny ram kommer att skapas enligt storleken på den aktuella bilden. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_1)(RasterImage) | Lägger till ny ram i slutet av den egna ramsamlingen. Innehållet i den nya ramen kommer att fyllas från den angivna bilden. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_2)(RasterImage, uint) | Lägger till ny ram i slutet av den egna ramsamlingen. Innehållet i den nya ramen kommer att fyllas från den angivna bilden. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage)(RasterImage) | Lägger till sida i bilden. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness)(int) | Justering av en*brightness* för bild. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) kontrasterande |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley#binarizebradley_1)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Cachelagrar data privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop)(Rectangle) | Beskär bilden. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop_1)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.imaging/datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.imaging/image/save) metod som den andra parametern. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Får en bildpixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Hämtar skevningsvinkeln. Denna metod är tillämplig på skannade textdokument, för att bestämma snedställningsvinkeln vid skanning. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale)() | Transformation av en bild till dess gråskalerepresentation |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe)(int) | Infogar ny ram i den egna ramsamlingen vid angivet index. En ny ram kommer att skapas enligt storleken på den aktuella bilden. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_1)(int, RasterImage) | Infogar ny ram i den egna ramsamlingen vid angivet index. Innehållet i den nya ramen kommer att fyllas från den angivna bilden. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_2)(int, RasterImage, uint) | Infogar ny ram i den egna ramsamlingen vid angivet index. Innehållet i den nya ramen kommer att fyllas från den angivna bilden. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat)(int) | Tar bort och returnerar ramen vid det angivna indexet för den egna ramsamlingen. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes)() | Tar bort alla ramar från den egna ramsamlingen. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat)(int) | Tar bort ramen vid det angivna indexet för den egna ramsamlingen. Ramen som ska tas bort kommer att kasseras. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage)() | Tar bort en tidigare inställd standardbild. Efter detta är standardbilden den första bildrutan i den egna ramsamlingen (den kan inte tas bort med den här metoden). |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändrar storleken på bilden. StandardenNearestNeighbourResample används. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate bild runt mitten. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip)(RotateFlipType) | Roterar, vänder eller roterar och vänder endast den aktiva ramen. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage)(RasterImage) | Ställer in den angivna rasterbilden som standardbild för den aktuella animationen. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konverterar rasterbilden till bitmappen. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Exempel

Följande exempel visar hur man exporterar apng APNG-filformat från andra icke-animerade flersidiga format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Ställa in standardbildlängden
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

Följande exempel visar hur man exporterar till APNG-filformat.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Exportera till APNG-animering med obegränsade animeringscykler som standard
    image.Save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cykler
}
```

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

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namnutrymme [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
