---
title: Codec
second_title: Aspose.Imaging für .NET-API-Referenz
description: Holt oder setzt den JPEG2000-Codec
type: docs
weight: 20
url: /de/net/aspose.imaging.imageoptions/jpeg2000options/codec/
---
## Jpeg2000Options.Codec property

Holt oder setzt den JPEG2000-Codec

```csharp
public Jpeg2000Codec Codec { get; set; }
```

### Eigentumswert

Der JPEG2000-Codec

### Beispiele

Dieses Beispiel zeigt, wie Sie ein PNG-Bild erstellen und es mit den gewünschten Optionen in JPEG2000 speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Verwenden Sie die irreversible diskrete Wavelet-Transformation 9-7
    saveOptions.Irreversible = true;

    // JP2 ist das "Container"-Format für JPEG 2000-Codestreams.
    // J2K sind komprimierte Rohdaten ohne Wrapper.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // In einer Datei speichern
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Dieses Beispiel zeigt, wie Sie ein JPEG2000-Bild mit den gewünschten Optionen erstellen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Verwenden Sie die irreversible diskrete Wavelet-Transformation 9-7
createOptions.Irreversible = true;

// JP2 ist das "Container"-Format für JPEG 2000-Codestreams.
// J2K sind komprimierte Rohdaten ohne Wrapper.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Erstellen Sie ein JPEG2000-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // In einer Datei speichern
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Siehe auch

* enum [Jpeg2000Codec](../../../aspose.imaging.fileformats.jpeg2000/jpeg2000codec)
* class [Jpeg2000Options](../../jpeg2000options)
* namensraum [Aspose.Imaging.ImageOptions](../../jpeg2000options)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
