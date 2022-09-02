---
title: ResolutionSettings
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Auflösungseinstellungen ab oder legt sie fest.
type: docs
weight: 60
url: /de/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Ruft die Auflösungseinstellungen ab oder legt sie fest.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

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

Das folgende Beispiel zeigt, wie Sie ein JPEG-Bild der angegebenen Größe mit den angegebenen Parametern erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein JPEG-Bild mit 100 x 100 Pixel.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Die Anzahl der Bits pro Kanal ist entsprechend 8, 8, 8 für Y-, Cr-, Cb-Komponenten.
createOptions.BitsPerChannel = 8;

// Legen Sie den progressiven Komprimierungstyp fest.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Stellen Sie die Bildqualität ein. Es ist ein Wert zwischen 1 und 100.
createOptions.Quality = 100;

// Legen Sie die horizontale/vertikale Auflösung auf 96 Punkte pro Zoll fest.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, unterabgetastet, komprimiert werden.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Das Bild mit einem Graustufenverlauf füllen
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // In einer Datei speichern.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Siehe auch

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* namensraum [Aspose.Imaging](../../imageoptionsbase)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
