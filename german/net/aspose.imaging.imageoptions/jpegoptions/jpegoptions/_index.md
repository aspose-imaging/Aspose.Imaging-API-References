---
title: JpegOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonJpegOptionsaspose.imaging.imageoptions/jpegoptions Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.imageoptions/jpegoptions/jpegoptions/
---
## JpegOptions() {#constructor}

Initialisiert eine neue Instanz von[`JpegOptions`](../../jpegoptions) Klasse.

```csharp
public JpegOptions()
```

### Beispiele

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

* class [JpegOptions](../../jpegoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../jpegoptions)
* Montage [Aspose.Imaging](../../../)

---

## JpegOptions(JpegOptions) {#constructor_1}

Initialisiert eine neue Instanz von[`JpegOptions`](../../jpegoptions) Klasse.

```csharp
public JpegOptions(JpegOptions jpegOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpegOptions | JpegOptions | Die JPEG-Optionen. |

### Siehe auch

* class [JpegOptions](../../jpegoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../jpegoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
