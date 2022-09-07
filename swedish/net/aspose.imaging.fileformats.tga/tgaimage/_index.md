---
title: TgaImage
second_title: Aspose.Imaging för .NET API-referens
description: TGA-bilden.
type: docs
weight: 7580
url: /sv/net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

TGA-bilden.

```csharp
public class TgaImage : RasterCachedImage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TgaImage](tgaimage#constructor)(RasterImage) | Initierar en ny instans av[`TgaImage`](../tgaimage) class. |
| [TgaImage](tgaimage#constructor_1)(Stream) | Initierar en ny instans av[`TgaImage`](../tgaimage) class. |
| [TgaImage](tgaimage#constructor_2)(string) | Initierar en ny instans av[`TgaImage`](../tgaimage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments) { get; set; } | Hämtar eller sätter författarekommentarer. Detta är ett ASCII-fält som består av 324 byte som är organiserade som fyra rader med 80 tecken, var och en följt av en nollterminator. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname) { get; set; } | Hämtar eller ställer in författarens namn. Detta fält är totalt 40 ASCII-tecken för namnet. Om fältet används, ska det innehålla namnet på personen som skapade bilden (författare). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor) { get; set; } | Hämtar eller ställer in bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel) { get; } | Får bitar per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel) { get; } | Får byte per pixel. |
| [Container](../../aspose.imaging/image/container) { get; } | Får[`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Hämtar objektets dataström. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp) { get; set; } | Hämtar eller ställer in datum/tidsstämpel. Det här fältet definierar värdet för datum och tid då bilden sparades. Även om operativsystem vanligtvis tids- och datumstämpelfiler tillhandahålls den här funktionen eftersom operativsystemet kan ändra tids- och datumstämpeln om filen kopieras. Genom att använda detta område är du garanterad en omodifierad region för datum och tid inspelning. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat) { get; } | Hämtar filformatet. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator) { get; } | Får Gamma Value Denominator part. En okorrigerad bild (en bild utan gamma) bör ha värdet 1.0 som resultat. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator) { get; } | Får Gamma Value Numerator-del. En okorrigerad bild (en bild utan gamma) bör ha värdet 1.0 som resultat. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha) { get; } | Får ett värde som indikerar om detta[`TgaImage`](../tgaimage) har en alfakanal. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap) { get; } | Får ett värde som indikerar om denna bild har färgkarta. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har transparent färg. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height) { get; } | Får denna bildhöjd. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid) { get; set; } | Hämtar eller ställer in bild-ID. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Får opacitet för denna bild. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale) { get; } | Får ett värde som indikerar om detta[`TgaImage`](../tgaimage) är gråskala. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid) { get; set; } | Hämtar eller ställer in jobbnamn/ID. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime) { get; set; } | Hämtar eller ställer in jobbtid. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator) { get; } | Får Pixel Aspect Ratio nämnardelen. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator) { get; } | Får Pixel Aspect Ratio täljardel. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Hämtar den rå radstorleken i byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Hämtar bildstorleken. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid) { get; set; } | Hämtar eller ställer in programvaru-ID. Totalt 40 ASCII-tecken för programvaru-ID. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion) { get; set; } | Hämtar eller ställer in mjukvaruversion. Godkänd versionsstränglängd är 3-4 tecken. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter) { get; set; } | Hämtar eller ställer in programvaruversionens bokstavsdel. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber) { get; set; } | Hämtar eller ställer in programvaruversionsnummer del. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor) { get; set; } | Hämtar eller ställer in nyckelfärg. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Får ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width) { get; } | Får denna bildbredd. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadata. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin) { get; set; } | Hämtar eller ställer in absoluta horisontella koordinater för det nedre vänstra hörnet av image när den är placerad på en visningsenhet som har ett ursprung längst ned till vänster på skärmen (t.ex. TARGA-serien). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin) { get; set; } | Hämtar eller ställer in absoluta vertikala koordinater för det nedre vänstra hörnet av image när den är placerad på en visningsenhet som har ett ursprung längst ned till vänster på skärmen (t.ex. TARGA-serien). |

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
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone)() | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone_1)(TgaImage) | Klona annat[`TgaImage`](../tgaimage) objektets egenskaper. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop)(Rectangle) | Beskär bilden. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop_1)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals_1)(object) | Jämställdhetsjämförelse. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals)(TgaImage) | Jämställdhetsjämförelse. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode)() | Hämta hashkod för denna instans. Inte lämplig att användas som nyckel som[`TgaImage`](../tgaimage) är inte oföränderlig. |
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
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. StandardenNearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate bild runt mitten. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip)(RotateFlipType) | Den roterande flippen. |
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
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality) | Jämställdhetsjämförelse. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality) | Icke-jämlikhet jämförelse. |

### Exempel

Spara JPG-bilden som en TGA-bild.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Laddar PNG-bilden, konvertering av den till TgaImage och sparar som en TGA-bild.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Uppdaterar offentliga egenskaper för den inlästa TGA-bilden.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Hämta värden för de offentliga egenskaperna för den inlästa TGA-bilden.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Se även

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
