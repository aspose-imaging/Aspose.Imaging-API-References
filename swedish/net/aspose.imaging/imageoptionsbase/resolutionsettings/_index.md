---
title: ResolutionSettings
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in upplösningsinställningarna.
type: docs
weight: 60
url: /sv/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Hämtar eller ställer in upplösningsinställningarna.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Exempel

Följande exempel laddar en BMP-bild och sparar den tillbaka till BMP med hjälp av olika sparalternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Skapa BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Använd 8 bitar per pixel för att minska storleken på utdatabilden.
    saveOptions.BitsPerPixel = 8;

    // Ställ in den närmaste 8-bitars färgpalett som täcker det maximala antalet bildpixlar, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Spara utan komprimering.
    // Du kan också använda RLE-8-komprimering för att minska storleken på den utgående bilden.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Ställ in den horisontella och vertikala upplösningen till 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

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

Följande exempel skapar en palettiserad BMP-bild i gråskala och sparar den sedan i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Spara till en fil
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Använd 8 bitar per pixel för att minska storleken på utdatabilden.
createOptions.BitsPerPixel = 8;

// Ställ in standard 8-bitars gråskalefärgpalett som täcker alla gråskalefärger.
// Om den bearbetade bilden endast innehåller gråskalefärger, då dess palettiserade version
// är visuellt omöjlig att skilja från en icke-palletiserad.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Spara utan komprimering.
// Du kan också använda RLE-8-komprimering för att minska storleken på den utgående bilden.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Ställ in den horisontella och vertikala upplösningen till 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Skapa en BMP-bild på 100 x 100 px och spara den i en fil.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Fyll bilden med en gråskalegradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
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

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* namnutrymme [Aspose.Imaging](../../imageoptionsbase)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
