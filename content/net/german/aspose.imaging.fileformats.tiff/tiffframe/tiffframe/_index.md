---
title: TiffFrame
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonTiffFrameaspose.imaging.fileformats.tiff/tiffframe Klasse.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem ein Bild geladen und Framepixel- und Palettendaten initialisiert werden sollen. |

### Siehe auch

* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem ein Bild geladen und Framepixel- und Palettendaten initialisiert werden sollen. |
| options | TiffOptions | Die für den neu erstellten Rahmen zu verwendenden Optionen. |

### Siehe auch

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes und zum Initialisieren von Rahmenpixel- und Palettendaten. |

### Siehe auch

* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes und zum Initialisieren von Rahmenpixel- und Palettendaten. |
| options | TiffOptions | Die für den neu erstellten Rahmen zu verwendenden Optionen. |

### Siehe auch

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(RasterImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild, mit dem Bildpixel und Palettendaten initialisiert werden sollen. |

### Beispiele

Das folgende Beispiel zeigt, wie aus einzelnen Rasterbildern ein mehrseitiges TIFF zusammengesetzt wird.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Dies ist Schriftart und Pinsel zum Zeichnen von Text auf einzelnen Rahmen.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // 5 Frames erstellen
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Erstellen Sie ein PNG-Bild und zeichnen Sie die Seitenzahl darauf.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Erstellen Sie einen Rahmen basierend auf dem PNG-Bild.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Rahmen zum TIFF-Bild hinzufügen.
        tiffImage.AddFrame(frame);
    }

    // Das Bild wurde mit einem einzelnen Standardrahmen erstellt. Entfernen wir es.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Vergessen Sie nicht, den Rahmen zu entsorgen, wenn Sie ihn keinem anderen TiffImage hinzufügen
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild, mit dem Bildpixel und Palettendaten initialisiert werden sollen. |
| options | TiffOptions | Die für den neu erstellten Rahmen zu verwendenden Optionen. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Initialisiert eine neue Instanz von[`TiffFrame`](../../tiffframe) Klasse.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | TiffOptions | Die Rahmenoptionen. |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Optionsparameter ist null. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein TIFF-Bild von Grund auf neu erstellen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Setze 8 Bits für jede Farbkomponente.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Lege die Big-Endian-Byte-Reihenfolge fest (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Legen Sie die LZW-Komprimierung fest.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Legen Sie das RGB-Farbmodell fest.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Erstellen Sie einen TIFF-Frame von 100 x 100 px.
// Beachten Sie, dass Sie einen Rahmen nicht explizit löschen müssen, wenn er in TiffImage enthalten ist.
// Wenn der Container entsorgt wird, werden alle Frames automatisch entsorgt.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Füllen Sie den gesamten Rahmen mit dem blau-gelben Farbverlauf.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Erstellen Sie ein TIFF-Bild.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

Dieses Beispiel zeigt, wie Sie ein TIFF-Bild mit 2 Frames erstellen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Optionen für den ersten Frame
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Setze 8 Bits für jede Farbkomponente.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Lege die Big-Endian-Byte-Reihenfolge fest (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Legen Sie die LZW-Komprimierung fest.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Legen Sie das RGB-Farbmodell fest.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Erstellen Sie den ersten TIFF-Frame von 100 x 100 px.
// Beachten Sie, dass Sie Frames nicht explizit löschen müssen, wenn sie in TiffImage enthalten sind.
// Wenn der Container entsorgt wird, werden alle Frames automatisch entsorgt.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Den ersten Frame mit dem blau-gelben Farbverlauf füllen.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Optionen für den ersten Frame
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Setze 1 Bit pro Pixel für ein S/W-Bild.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Setze die Little-Endian-Byte-Reihenfolge (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Legen Sie die CCITT-Gruppe 3-Faxkomprimierung fest.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Stellen Sie das S/W-Farbmodell ein, wobei 0 schwarz und 1 weiß ist.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Erstellen Sie den zweiten TIFF-Frame mit 200 x 200 Pixel.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Füllen Sie den zweiten Frame mit dem blau-gelben Farbverlauf.
// Es wird aufgrund der entsprechenden Einstellungen des Rahmens automatisch in das S/W-Format konvertiert.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Erstellen Sie ein TIFF-Bild.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Siehe auch

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
