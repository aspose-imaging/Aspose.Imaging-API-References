---
title: GifOptions
second_title: Aspose.Imaging för .NET API-referens
description: Alternativen för att skapa gif-filformat.
type: docs
weight: 10000
url: /sv/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Alternativen för att skapa gif-filformat.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Initierar en ny instans av[`GifOptions`](../gifoptions) class. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Initierar en ny instans av[`GifOptions`](../gifoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Hämtar eller ställer in bakgrundsfärgen. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Hämtar eller ställer in GIF-bakgrundsfärgindex. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Hämtar eller ställer in GIF-färgupplösningen. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Hämtar eller ställer in ett värde som anger om palettkorrigering tillämpas. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Hämtar eller ställer in ett värde som anger om GIF har trailer. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Hämtar eller ställer in ett värde som anger om GIF-bilden har transparent färg. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Sant om bilden ska vara sammanflätad. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Hämtar eller ställer in ett värde som anger om palettposter är sorterade. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Hämtar eller ställer in antalet loopar (Standard 1 loop) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Hämtar eller ställer in den maximala tillåtna pixelskillnaden. Om den är större än noll kommer förlustkomprimering att användas. Rekommenderat värde för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung. Det fungerar bäst när endast liten förlust introduceras, och på grund av begränsning av komprimeringsalgoritmen mycket höga förlustnivåer ger inte lika mycket förstärkning. Intervallet för tillåtna värden är [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Hämtar eller ställer in GIF-pixelns bildförhållande. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar användningen av olika klasser från SaveOptions Namespace för exportändamål. En bild av typen Gif laddas in i en instans av Image och exporteras sedan ut till flera format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Ladda in en befintlig bild (av typen Gif) i en instans av klassen Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Exportera till BMP-filformat med standardalternativen
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Exportera till JPEG-filformat med standardalternativen
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Exportera till PNG-filformat med standardalternativen
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Exportera till TIFF-filformat med standardalternativen
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Följande exempel visar hur man konverterar en flersidig vektorbild till GIF-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som animerade ramar i utdata-GIF.
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

Det här exemplet visar hur man laddar pixelinformation i en array av typfärg, manipulerar arrayen och återställer den till bilden. För att utföra dessa operationer skapar det här exemplet en ny bildfil (i GIF-format) med ett MemoryStream-objekt.

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av GifOptions och ställ in dess olika egenskaper inklusive egenskapen Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Hämta pixlarna i bilden genom att ange området som bildgräns
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Slinga över Arrayen och ställer in färgen på alrenativt indexerad pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ställ in den indexerade pixelfärgen till gul
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Ställ in den indexerade pixelfärgen till blå
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Tillämpa pixeländringarna på bilden
        image.SavePixels(image.Bounds, pixels);

        // spara alla ändringar.
        image.Save();
    }

    // Skriv MemoryStream till fil
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Se även

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
