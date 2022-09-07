---
title: Width
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar bildens bredd.
type: docs
weight: 110
url: /sv/net/aspose.imaging.fileformats.bmp/bmpimage/width/
---
## BmpImage.Width property

Hämtar bildens bredd.

```csharp
public override int Width { get; }
```

### Fastighetsvärde

Bildens bredd.

### Exempel

Följande exempel får allmän information om bilden inklusive pixelformat, bildstorlek, upplösning, komprimering etc.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // Du kan överväga att använda metoden SetResolution för att uppdatera båda upplösningsvärdena i ett enda samtal.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //Utgången kan se ut så här:
    //Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
    //Radstorleken i byte: 1500
    //Bitmappskomprimeringen: Rgb
    //Bitmappens bredd: 500
    //Bitmappshöjden: 375
    //Antalet bitar per pixel: 24
    //Den horisontella upplösningen, i pixlar per tum: 0
    //Den vertikala upplösningen, i pixlar per tum: 0
    //Ställ in upplösningsvärdena till 96 dpi
    //Den horisontella upplösningen, i pixlar per tum: 96,012
    //Den vertikala upplösningen, i pixlar per tum: 96,012
}
```

Följande exempel visar hur bitmappskomprimeringen påverkar storleken på utdatabilden.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Skapa en monokrom palett som endast innehåller röda och gröna färger.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Skapa en 8-bpp BMP-bild på 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Fyll hela bilden i rött.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Spara bilden i en ström för att få utdatabildens storlek.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// Utgången ser ut så här:
// -----------------------------------------------------------
// Kompressionen = Rgb
// Antalet bitar per pixel = 8
// Bildens mått = 100 x 100
// Den råa radstorleken = 100
// Utdatastorleken i byte = 11078
// -----------------------------------------------------------
// Kompressionen = Rle8
// Antalet bitar per pixel = 8
// Bildens mått = 100 x 100
// Den råa radstorleken = 100
// Utdatastorleken i byte = 856
```

### Se även

* class [BmpImage](../../bmpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
