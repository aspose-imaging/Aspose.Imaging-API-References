---
title: BitsPerPixel
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in bildbitar per pixelantal.
type: docs
weight: 20
url: /sv/aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

Hämtar eller ställer in bildbitar per pixelantal.

```csharp
public int BitsPerPixel { get; set; }
```

### Fastighetsvärde

Antalet bildbitar per pixel.

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

Följande exempel visar hur man palleterar en BMP-bild för att minska dess utdatastorlek.

```csharp
[C#]

// Skapa en BMP-bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll hela bilden med den linjära gradientpenseln.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Få den närmaste 8-bitars färgpalett som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-bitars palett innehåller högst 256 färger.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Utgången ser ut så här:
// Den palettiserade bildstorleken är 11078 byte.
// Den icke-palettiserade bildstorleken är 40054 byte.
```

### Se även

* class [BmpOptions](../../bmpoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../bmpoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
