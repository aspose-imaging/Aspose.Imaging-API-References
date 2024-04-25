---
title: PngImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPngImageaspose.imaging.fileformats.png/pngimage Klasse.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein PNG-Bild der angegebenen Größe erstellen, es mit einer Volltonfarbe füllen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Etwas Bildbearbeitung durchführen, z. B. das gesamte Bild rot füllen.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // In einer Datei speichern.
    pngImage.Save(dir + "output.png");
}
```

### Siehe auch

* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes. |

### Beispiele

Dieses Beispiel zeigt, wie ein PNG-Bild aus einer Datei geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein PNG-Bild aus einer Datei.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Bild in Graustufendarstellung umwandeln
    pngImage.Grayscale();

    // In einer Datei speichern.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Siehe auch

* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Rasterbild. |

### Beispiele

Dieses Beispiel zeigt, wie ein PNG-Bild aus einem BMP-Bild geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein TrueColor-PNG-Bild aus einem BMP-Bild.
// Erstellen Sie zuerst ein temporäres BMP-Bild, das als Grundlage für die Erstellung eines PNG-Bildes dient.
// Sie können auch ein BMP-Bild aus einer Datei laden oder ein Bild in einem anderen Rasterformat verwenden.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Das gesamte BMP-Bild rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes. |
| colorType | PngColorType | Der Farbtyp. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException |  |

### Beispiele

Dieses Beispiel zeigt, wie ein PNG-Bild aus einer Datei mit dem angegebenen Farbtyp geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein PNG-Bild aus einer Datei.
// Beachten Sie, dass das bunte Bild automatisch in Graustufen umgewandelt wird.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // In einer Datei speichern.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Siehe auch

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Rasterbild. |
| colorType | PngColorType | Der Farbtyp. |

### Beispiele

Dieses Beispiel zeigt, wie ein PNG-Bild aus einem BMP-Bild mit dem angegebenen Farbtyp geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein Graustufen-PNG-Bild aus einem farbigen BMP-Bild.
// Erstellen Sie zuerst ein temporäres BMP-Bild, das als Grundlage für die Erstellung eines PNG-Bildes dient.
// Sie können auch ein BMP-Bild aus einer Datei laden oder ein Bild in einem anderen Rasterformat verwenden.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Das gesamte BMP-Bild rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Die Farben der Bildpixel werden in ihre Graustufen-Gegenstücke konvertiert.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden eines Bildes. |

### Beispiele

Dieses Beispiel zeigt, wie ein PNG-Bild aus einer Datei oder einem Dateistream geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein PNG-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Bild in Graustufendarstellung umwandeln
        pngImage.Grayscale();

        // In einer Datei speichern.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Siehe auch

* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |
| colorType | PngColorType | Der Farbtyp. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein PNG-Bild der angegebenen Größe mit dem angegebenen Farbtyp erstellen, es mit einer Volltonfarbe füllen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein Graustufen-PNG-Bild mit 100 x 100 Pixel.
// Alle Farben werden automatisch in das Graustufenformat konvertiert.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Etwas Bildbearbeitung durchführen, z. B. das gesamte Bild rot füllen.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // In einer Datei speichern.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Siehe auch

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Initialisiert eine neue Instanz von[`PngImage`](../../pngimage) Klasse.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pngOptions | PngOptions | Die PNG-Optionen. |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein PNG-Bild mit den angegebenen Optionen erstellen, es mit linearen Verlaufsfarben füllen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Die Anzahl der Bits pro Farbkanal
createOptions.BitDepth = 8;

// Jedes Pixel ist ein (rot, grün, blau) Tripel, gefolgt von der Alpha-Komponente.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Die maximale Komprimierungsstufe.
createOptions.CompressionLevel = 9;

// Die Verwendung von Filtern ermöglicht es, kontinuierlich tonale Bilder effektiver zu komprimieren.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Progressives Laden verwenden
createOptions.Progressive = true;

// Erstellen Sie ein PNG-Bild mit benutzerdefinierten Parametern.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Das Bild mit einem halbtransparenten Farbverlauf füllen.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // In einer Datei speichern.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Siehe auch

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* namensraum [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
