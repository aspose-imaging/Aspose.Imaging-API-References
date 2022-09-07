---
title: JpegImage
second_title: Aspose.Imaging för .NET API-referens
description: En jpeg-bild.
type: docs
weight: 6770
url: /sv/net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

En jpeg-bild.

```csharp
public sealed class JpegImage : RasterCachedImage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [JpegImage](jpegimage#constructor_1)(RasterImage) | Initierar en ny instans av[`JpegImage`](../jpegimage) class. |
| [JpegImage](jpegimage#constructor_3)(Stream) | Initierar en ny instans av[`JpegImage`](../jpegimage) class. |
| [JpegImage](jpegimage#constructor_4)(string) | Initierar en ny instans av[`JpegImage`](../jpegimage) class. |
| [JpegImage](jpegimage#constructor_2)(int, int) | Initierar en ny instans av[`JpegImage`](../jpegimage) class. |
| [JpegImage](jpegimage#constructor)(JpegOptions, int, int) | Initierar en ny instans av[`JpegImage`](../jpegimage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile) { get; set; } | CMYK-färgprofilen för CMYK- och YCCK-jpeg-bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment) { get; set; } | Hämtar eller ställer in jpeg-filkommentaren. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile) { get; set; } | CMYK-färgprofilen för CMYK- och YCCK-jpeg-bilder, som används för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile) { get; set; } | RGB-färgprofilen för CMYK- och YCCK-jpeg-bilder, som används för att spara bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata) { get; set; } | Hämta eller ställ in exif data container |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat) { get; } | Får värdet filformat |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | Får ett värde som indikerar om denna instans har alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor) { get; set; } | Får ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height) { get; } | Hämtar bildhöjden. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile) { get; set; } | Hämtar eller ställer in ett värde som anger om den inbäddade färgprofilen ignoreras. Om den inbäddade färgprofilen ignoreras, används standardfärgprofilen. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Får opacitet för denna bild. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif) { get; set; } | Hämtar eller ställer in jfif. |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions) { get; } | Hämtar JPEG-alternativen som används för att skapa eller ladda detta[`JpegImage`](../jpegimage) instans. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Hämtar den rå radstorleken i byte. |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile) { get; set; } | RGB-färgprofilen för CMYK- och YCCK-jpeg-bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Får bilden genomskinlig färg. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width) { get; } | Hämtar bildens bredd. |
| override [XmpData](../../aspose.imaging.fileformats.jpeg/jpegimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Justera en ljusstyrka för bilden. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Bild kontrasterande |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Gamma-korrigering av en bild. |
| [AutoRotate](../../aspose.imaging.fileformats.jpeg/jpegimage/autorotate)() | Utför automatisk rotering av bilden beroende på orienteringsdata från Exif. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskelvärdet |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
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
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konverterar rasterbilden till bitmappen. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Exempel

Få åtkomst till anteckningar från kameratillverkaren i Jpeg-bild.

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

Exemplet visar hur man laddar en JpegImage från en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG-bild från en fil.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Gör lite bildbehandling.
    // Spara till en annan JPEG-fil.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Se även

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
