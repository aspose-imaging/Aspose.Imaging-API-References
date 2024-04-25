---
title: BitsPerPixel
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene il numero di bit dellimmagine per pixel.
type: docs
weight: 30
url: /it/aspose.imaging.fileformats.bmp/bmpimage/bitsperpixel/
---
## BmpImage.BitsPerPixel property

Ottiene il numero di bit dell'immagine per pixel.

```csharp
public override int BitsPerPixel { get; }
```

### Valore della proprietà

I bit dell'immagine per pixel contano.

### Esempi

L'esempio seguente ottiene le informazioni generali sull'immagine, inclusi il formato dei pixel, la dimensione dell'immagine, la risoluzione, la compressione, ecc.

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
        // Potresti prendere in considerazione l'utilizzo del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //L'output potrebbe essere simile a questo:
    //Il formato pixel: Rgb24Bpp, canali utilizzati: 8,8,8
    //La dimensione della riga grezza in byte: 1500
    //La compressione bitmap: Rgb
    //La larghezza della bitmap: 500
    //L'altezza della bitmap: 375
    //Il numero di bit per pixel: 24
    //La risoluzione orizzontale, in pixel per pollice: 0
    //La risoluzione verticale, in pixel per pollice: 0
    //Imposta i valori di risoluzione a 96 dpi
    //La risoluzione orizzontale, in pixel per pollice: 96.012
    //La risoluzione verticale, in pixel per pollice: 96.012
}
```

L'esempio seguente mostra come la compressione bitmap influisce sulla dimensione dell'immagine di output.

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

// Crea una tavolozza monocromatica che contenga solo i colori rosso e verde.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Crea un'immagine BMP a 8 bpp di 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Riempi di rosso l'intera immagine.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Salva l'immagine in un flusso per ottenere la dimensione dell'immagine di output.
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

// L'output è simile a questo:
// -----------------------------------------------
// La compressione = Rgb
// Il numero di bit per pixel = 8
// Le dimensioni dell'immagine = 100 x 100
// La dimensione della linea grezza = 100
// La dimensione dell'output in byte = 11078
// -----------------------------------------------
// La compressione = Rle8
// Il numero di bit per pixel = 8
// Le dimensioni dell'immagine = 100 x 100
// La dimensione della linea grezza = 100
// La dimensione dell'output in byte = 856
```

### Guarda anche

* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
