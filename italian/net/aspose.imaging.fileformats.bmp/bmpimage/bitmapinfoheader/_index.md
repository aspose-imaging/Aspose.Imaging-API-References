---
title: BitmapInfoHeader
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene lintestazione delle informazioni bitmap.
type: docs
weight: 20
url: /it/net/aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/
---
## BmpImage.BitmapInfoHeader property

Ottiene l'intestazione delle informazioni bitmap.

```csharp
public BitmapInfoHeader BitmapInfoHeader { get; }
```

### Valore della proprietà

L'intestazione delle informazioni bitmap.

### Esempi

L'esempio seguente ottiene le informazioni dall'intestazione BMP e le stampa sulla console.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    Aspose.Imaging.FileFormats.Bmp.BitmapInfoHeader header = bmpImage.BitmapInfoHeader;

    System.Console.WriteLine("The number of palette colors that are required for displaying the bitmap: {0}", header.BitmapColorsImportant);
    System.Console.WriteLine("The number of palette colors used in the bitmap: {0}", header.BitmapColorsUsed);
    System.Console.WriteLine("The bitmap compression: {0}", header.BitmapCompression);
    System.Console.WriteLine("The bitmap height: {0}", header.BitmapHeight);
    System.Console.WriteLine("The bitmap width: {0}", header.BitmapWidth);
    System.Console.WriteLine("The bitmap raw data size in bytes: {0}", header.BitmapImageSize);
    System.Console.WriteLine("The number of planes: {0}", header.BitmapPlanes);
    System.Console.WriteLine("The horizontal resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapXPelsPerMeter);
    System.Console.WriteLine("The vertical resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapYPelsPerMeter);
    System.Console.WriteLine("The number of bits per pixel: {0}", header.BitsPerPixel);
    System.Console.WriteLine("The extra bits masks: {0}", header.ExtraBitMasks);
    System.Console.WriteLine("The header size in bytes: {0}", header.HeaderSize);
}

//L'output potrebbe essere simile a questo:
//Il numero di colori della tavolozza necessari per visualizzare la bitmap: 0
//Il numero di colori della tavolozza utilizzati nella bitmap: 0
//La compressione bitmap: 0
//L'altezza della bitmap: 375
//La larghezza della bitmap: 500
//La dimensione dei dati grezzi bitmap in byte: 562500
//Il numero di aerei: 1
//La risoluzione orizzontale della bitmap, in pixel per metro: 0
//La risoluzione verticale della bitmap, in pixel per metro: 0
//Il numero di bit per pixel: 24
//Le maschere di bit extra: 
//La dimensione dell'intestazione in byte: 40
```

### Guarda anche

* class [BitmapInfoHeader](../../bitmapinfoheader)
* class [BmpImage](../../bmpimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->