---
title: ColorType
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in färgtypen för jpeg-bild.
type: docs
weight: 40
url: /sv/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

Hämtar eller ställer in färgtypen för jpeg-bild.

```csharp
public JpegCompressionColorMode ColorType { get; set; }
```

### Exempel

Följande exempel laddar en BMP-bild och sparar den till JPEG med hjälp av olika sparalternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en BMP-bild från en fil.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Gör lite bildbehandling.

    // Använd ytterligare alternativ för att ange önskade bildparametrar.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.BitsPerChannel = 8;

    // Ställ in den progressiva typen av komprimering.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Ställ in bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.Quality = 100;

    // Ställ in den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Använd en palett för att minska utdatastorleken.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

Följande exempel laddar PNG och sparar det till CMYK JPEG med hjälp av anpassad ICC-profil. Laddar sedan CMYK JPEG och sparar den tillbaka till PNG. Färgkonverteringen från RGB till CMYK och från CMYK till RGB utförs med hjälp av anpassade ICC-profiler.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda PNG och spara den i CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // Använd anpassade ICC-profiler
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// Ladda CMYK JPEG och spara den till PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // Använd anpassade ICC-profiler
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
}
```

Följande exempel visar hur man skapar en JPEG-bild av den angivna storleken med de angivna parametrarna.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en JPEG-bild på 100x100 px.
// Använd ytterligare alternativ för att ange önskade bildparametrar.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y, Cr, Cb komponenter i enlighet därmed.
createOptions.BitsPerChannel = 8;

// Ställ in den progressiva typen av komprimering.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Ställ in bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.Quality = 100;

// Ställ in den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Detta är ett standardalternativ för JPEG-bilder.
// Två chroma-komponenter (Cb och Cr) kan bandbreddsreduceras, subsamplas, komprimeras.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Fyll bilden med en gråskalegradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Spara till en fil.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Se även

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode)
* class [JpegOptions](../../jpegoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../jpegoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
