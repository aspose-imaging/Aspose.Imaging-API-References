---
title: Height
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Bildhöhe ab.
type: docs
weight: 60
url: /de/aspose.imaging.fileformats.bmp/bmpimage/height/
---
## BmpImage.Height property

Ruft die Bildhöhe ab.

```csharp
public override int Height { get; }
```

### Eigentumswert

Die Bildhöhe.

### Beispiele

Das folgende Beispiel ruft die allgemeinen Informationen über das Bild ab, einschließlich Pixelformat, Bildgröße, Auflösung, Komprimierung usw.

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
        // Sie können die SetResolution-Methode verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //Die Ausgabe könnte so aussehen:
    //Das Pixelformat: RGB24Bpp, verwendete Kanäle: 8,8,8
    //Die Rohzeilengröße in Bytes: 1500
    //Die Bitmap-Komprimierung: Rgb
    //Die Bitmap-Breite: 500
    //Die Bitmap-Höhe: 375
    //Die Anzahl der Bits pro Pixel: 24
    //Die horizontale Auflösung in Pixel pro Zoll: 0
    //Die vertikale Auflösung in Pixel pro Zoll: 0
    //Auflösungswerte auf 96 dpi setzen
    //Die horizontale Auflösung in Pixel pro Zoll: 96.012
    //Die vertikale Auflösung in Pixel pro Zoll: 96.012
}
```

Das folgende Beispiel zeigt, wie sich die Bitmap-Komprimierung auf die Ausgabebildgröße auswirkt.

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

// Erstellen Sie eine monochrome Palette, die nur rote und grüne Farben enthält.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Erstellen Sie ein 8-bpp-BMP-Bild mit 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Das gesamte Bild rot füllen.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Speichern Sie das Bild in einem Stream, um die Ausgabebildgröße zu erhalten.
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

// Die Ausgabe sieht so aus:
// ---------------------------------------------
// Die Komprimierung = RGB
// Die Anzahl der Bits pro Pixel = 8
// Die Bildabmessungen = 100 x 100
// Die Rohzeilengröße = 100
// Die Ausgabegröße in Bytes = 11078
// ---------------------------------------------
// Die Komprimierung = Rle8
// Die Anzahl der Bits pro Pixel = 8
// Die Bildabmessungen = 100 x 100
// Die Rohzeilengröße = 100
// Die Ausgabegröße in Bytes = 856
```

### Siehe auch

* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
