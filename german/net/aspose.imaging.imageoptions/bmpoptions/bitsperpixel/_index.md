---
title: BitsPerPixel
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Anzahl der Bildbits pro Pixel ab oder legt sie fest.
type: docs
weight: 20
url: /de/net/aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

Ruft die Anzahl der Bildbits pro Pixel ab oder legt sie fest.

```csharp
public int BitsPerPixel { get; set; }
```

### Eigentumswert

Die Bildbits pro Pixel zählen.

### Beispiele

Das folgende Beispiel lädt ein BMP-Bild und speichert es mit verschiedenen Speicheroptionen wieder in BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // BmpOptions erstellen
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Verwenden Sie 8 Bit pro Pixel, um die Größe des Ausgabebilds zu reduzieren.
    saveOptions.BitsPerPixel = 8;

    // Legen Sie die nächste 8-Bit-Farbpalette fest, die die maximale Anzahl von Bildpixeln abdeckt, sodass ein palettisiertes Bild entsteht
    // ist optisch kaum von einem nicht palettierten zu unterscheiden.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Ohne Komprimierung speichern.
    // Sie können auch die RLE-8-Komprimierung verwenden, um die Größe des Ausgabebilds zu reduzieren.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Legen Sie die horizontale und vertikale Auflösung auf 96 dpi fest.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

Das folgende Beispiel erstellt ein palettiertes Graustufen-BMP-Bild und speichert es dann in einer Datei.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// In einer Datei speichern
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Verwenden Sie 8 Bit pro Pixel, um die Größe des Ausgabebilds zu reduzieren.
createOptions.BitsPerPixel = 8;

// Legen Sie die standardmäßige 8-Bit-Graustufen-Farbpalette fest, die alle Graustufen-Farben abdeckt.
// Wenn das verarbeitete Bild nur Graustufenfarben enthält, dann seine palettierte Version
// ist optisch nicht von einem nicht palettierten zu unterscheiden.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Ohne Komprimierung speichern.
// Sie können auch die RLE-8-Komprimierung verwenden, um die Größe des Ausgabebilds zu reduzieren.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Legen Sie die horizontale und vertikale Auflösung auf 96 dpi fest.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Erstellen Sie ein BMP-Bild von 100 x 100 px und speichern Sie es in einer Datei.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Das Bild mit einem Graustufenverlauf füllen
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

Das folgende Beispiel zeigt, wie ein BMP-Bild palettiert wird, um seine Ausgabegröße zu reduzieren.

```csharp
[C#]

// Erstellen Sie ein BMP-Bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Füllen Sie das gesamte Bild mit dem linearen Verlaufspinsel.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Holen Sie sich die nächste 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, um ein palettisiertes Bild zu erhalten
    // ist optisch kaum von einem nicht palettierten zu unterscheiden.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-Bit-Palette enthält höchstens 256 Farben.
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

// Die Ausgabe sieht so aus:
// Die palettierte Bildgröße beträgt 11078 Bytes.
// Die nicht palettierte Bildgröße beträgt 40054 Byte.
```

### Siehe auch

* class [BmpOptions](../../bmpoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../bmpoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
