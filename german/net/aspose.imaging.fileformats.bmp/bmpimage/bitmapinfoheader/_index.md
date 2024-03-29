---
title: BitmapInfoHeader
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Bitmap-Informationsheader ab.
type: docs
weight: 20
url: /de/net/aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/
---
## BmpImage.BitmapInfoHeader property

Ruft den Bitmap-Informationsheader ab.

```csharp
public BitmapInfoHeader BitmapInfoHeader { get; }
```

### Eigentumswert

Der Bitmap-Informationsheader.

### Beispiele

Das folgende Beispiel ruft die Informationen aus dem BMP-Header ab und gibt sie auf der Konsole aus.

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

//Die Ausgabe könnte so aussehen:
//Die Anzahl der Palettenfarben, die zum Anzeigen der Bitmap benötigt werden: 0
//Die Anzahl der in der Bitmap verwendeten Palettenfarben: 0
//Die Bitmap-Komprimierung: 0
//Die Bitmap-Höhe: 375
//Die Bitmap-Breite: 500
//Die Bitmap-Rohdatengröße in Byte: 562500
//Die Anzahl der Flugzeuge: 1
//Die horizontale Auflösung der Bitmap in Pixel pro Meter: 0
//Die vertikale Auflösung der Bitmap in Pixel pro Meter: 0
//Die Anzahl der Bits pro Pixel: 24
//Die zusätzlichen Bits maskieren: 
//Die Header-Größe in Bytes: 40
```

### Siehe auch

* class [BitmapInfoHeader](../../bitmapinfoheader)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
