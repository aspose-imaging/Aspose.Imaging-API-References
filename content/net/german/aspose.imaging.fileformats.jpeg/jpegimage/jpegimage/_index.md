---
title: JpegImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonJpegImageaspose.imaging.fileformats.jpeg/jpegimage Klasse.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Initialisiert eine neue Instanz von[`JpegImage`](../../jpegimage) Klasse.

```csharp
public JpegImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Beispiele

Das Beispiel zeigt, wie ein JpegImage aus einer Datei geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein JPEG-Bild aus einer Datei.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Führen Sie eine Bildverarbeitung durch.
    // In einer anderen JPEG-Datei speichern.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Siehe auch

* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Initialisiert eine neue Instanz von[`JpegImage`](../../jpegimage) Klasse.

```csharp
public JpegImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Beispiele

Das Beispiel zeigt, wie ein JpegImage aus einem Dateistream geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein JPEG-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Führen Sie eine Bildverarbeitung durch.
        // In einer anderen JPEG-Datei speichern.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Siehe auch

* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Initialisiert eine neue Instanz von[`JpegImage`](../../jpegimage) Klasse.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, mit dem Pixel- und Palettendaten initialisiert werden sollen. |

### Beispiele

Das Beispiel zeigt, wie ein JpegImage aus einem anderen RasterImage geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein JPEG-Bild von einem anderen Rasterbild.
// Erstellen Sie zuerst ein temporäres PNG-Bild, das als Grundlage für die Erstellung eines JPEG-Bildes dient.
// Sie können auch ein PNG-Bild aus einer Datei laden oder ein Bild in einem anderen Rasterformat verwenden.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Das gesamte PNG-Bild rot füllen.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Erstellen Sie ein JPEG-Bild basierend auf dem PNG-Bild.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Speichern in einer JPEG-Datei
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Initialisiert eine neue Instanz von[`JpegImage`](../../jpegimage) Klasse.

```csharp
public JpegImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein JPEG-Bild der angegebenen Größe erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein JPEG-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Führen Sie eine Bildverarbeitung durch.
    // In einer Datei speichern.
    jpegImage.Save(dir + "output.jpg");
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

### Siehe auch

* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Initialisiert eine neue Instanz von[`JpegImage`](../../jpegimage) Klasse.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpegOptions | JpegOptions | Die JPEG-Optionen. |
| width | Int32 | Bildbreite. |
| height | Int32 | Bildhöhe. |

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* namensraum [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
