---
title: VerticalResolution
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta la risoluzione verticale in pixel per pollice di questoRasterImageaspose.imaging/rasterimage .
type: docs
weight: 100
url: /it/net/aspose.imaging.fileformats.bmp/bmpimage/verticalresolution/
---
## BmpImage.VerticalResolution property

Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override double VerticalResolution { get; set; }
```

### Valore della proprietà

La risoluzione verticale.

### Osservazioni

Nota per impostazione predefinita questo valore è sempre 96 poiché piattaforme diverse non possono restituire la risoluzione dello schermo. È possibile considerare l'utilizzo del metodo SetResolution per aggiornare entrambi i valori di risoluzione in un'unica chiamata.

### Esempi

L'esempio seguente mostra come impostare la risoluzione orizzontale/verticale di un'immagine BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;

    // Ottieni la risoluzione orizzontale e verticale di BmpImage
    double horizontalResolution = bmpImage.HorizontalResolution;
    double verticalResolution = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // L'output potrebbe essere simile a questo:
    // La risoluzione orizzontale, in pixel per pollice: 0
    // La risoluzione verticale, in pixel per pollice: 0
    // Imposta i valori di risoluzione su 96 dpi
    // La risoluzione orizzontale, in pixel per pollice: 96.012
    // La risoluzione verticale, in pixel per pollice: 96.012
}
```

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

### Guarda anche

* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
