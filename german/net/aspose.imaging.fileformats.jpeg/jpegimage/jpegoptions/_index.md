---
title: JpegOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die JPEG-Optionen ab die verwendet werden um dies zu erstellen oder zu ladenJpegImageaspose.imaging.fileformats.jpeg/jpegimage Instanz.
type: docs
weight: 130
url: /de/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

Ruft die JPEG-Optionen ab, die verwendet werden, um dies zu erstellen oder zu laden[`JpegImage`](../../jpegimage) Instanz.

```csharp
public JpegOptions JpegOptions { get; }
```

### Eigentumswert

Die JPEG-Optionen.

### Beispiele

Das folgende Beispiel zeigt, wie die Header-Informationen aus einem JPEG-Bild extrahiert werden.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

//Die Ausgabe sieht so aus:
//Die Anzahl der Bits pro Kanal: 8
//Die maximal zulässige Größe für alle internen Puffer: 0
//Der Farbtyp: YCbCr
//Der Komprimierungstyp: Baseline
//Die Bildqualität: 75
//Das Sampling für Komponente 0: 1x1
//Das Sampling für Komponente 1: 1x1
//Das Sampling für Komponente 2: 1x1
```

### Siehe auch

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
