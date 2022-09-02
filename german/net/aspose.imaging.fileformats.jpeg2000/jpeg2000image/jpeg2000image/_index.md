---
title: Jpeg2000Image
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Beispiele

Dieses Beispiel zeigt, wie ein JPEG2000-Bild aus einer Datei geladen und als PNG gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein JPEG2000-Bild.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Als PNG speichern
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten |
| bitsPerPixel | Int32 | Die Bits pro Pixel. |

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Beispiele

Dieses Beispiel zeigt, wie ein JPEG2000-Bild aus einem Dateistream geladen und als PNG gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein JPEG2000-Bild aus dem Stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Als PNG speichern
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |
| bitsPerPixel | Int32 | Die Bits pro Pixel. |

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite |
| height | Int32 | Die Bildhöhe |

### Beispiele

Dieses Beispiel zeigt, wie ein JPEG2000-Bild erstellt und in einer Datei gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein JPEG2000-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // In einer Datei speichern
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite |
| height | Int32 | Die Bildhöhe |
| options | Jpeg2000Options | Die Optionen. |

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

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite |
| height | Int32 | Die Bildhöhe |
| bitsCount | Int32 | Die Bits zählen. |

### Siehe auch

* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild. |

### Beispiele

Dieses Beispiel zeigt, wie Sie aus einem anderen Rasterbild ein JPEG2000-Bild erstellen.

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

    // Erstellen Sie ein JPEG2000-Bild basierend auf dem PNG-Bild.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // In einer Datei speichern
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Initialisiert eine neue Instanz von[`Jpeg2000Image`](../../jpeg2000image) Klasse.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, mit dem Pixel- und Palettendaten initialisiert werden sollen. |
| bitsPerPixel | Int32 | Die Bits pro Pixel. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namensraum [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
