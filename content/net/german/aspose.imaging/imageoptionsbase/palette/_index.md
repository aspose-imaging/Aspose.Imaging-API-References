---
title: Palette
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Farbpalette ab oder legt sie fest.
type: docs
weight: 40
url: /de/aspose.imaging/imageoptionsbase/palette/
---
## ImageOptionsBase.Palette property

Ruft die Farbpalette ab oder legt sie fest.

```csharp
public virtual IColorPalette Palette { get; set; }
```

### Eigentumswert

Die Farbpalette.

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein PNG-Bild komprimieren, indem Sie indizierte Farben mit der Palette „Best Fit“ verwenden

```csharp
[C#]

// PNG-Bild wird geladen        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Indizierten Farbtyp verwenden
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Maximale Komprimierung verwenden
         CompressionLevel = 9,
      // Holen Sie sich die nächste 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, um ein palettisiertes Bild zu erhalten
         // ist optisch kaum von einem nicht palettierten zu unterscheiden.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Die Größe der Ausgabedatei sollte erheblich reduziert werden
```

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

Das folgende Beispiel lädt ein BMP-Bild und speichert es unter Verwendung verschiedener Speicheroptionen im JPEG-Format.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Führen Sie eine Bildverarbeitung durch.

    // Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Die Anzahl der Bits pro Kanal beträgt 8.
    // Wenn eine Palette verwendet wird, wird der Farbindex anstelle der Farbe selbst in den Bilddaten gespeichert.
    saveOptions.BitsPerChannel = 8;

    // Legen Sie den progressiven Komprimierungstyp fest.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Stellen Sie die Bildqualität ein. Es ist ein Wert zwischen 1 und 100.
    saveOptions.Quality = 100;

    // Legen Sie die horizontale/vertikale Auflösung auf 96 Punkte pro Zoll fest.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Wenn das Quellbild farbig ist, wird es in Graustufen umgewandelt.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Verwenden Sie eine Palette, um die Ausgabegröße zu reduzieren.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
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

* interface [IColorPalette](../../icolorpalette)
* class [ImageOptionsBase](../../imageoptionsbase)
* namensraum [Aspose.Imaging](../../imageoptionsbase)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
