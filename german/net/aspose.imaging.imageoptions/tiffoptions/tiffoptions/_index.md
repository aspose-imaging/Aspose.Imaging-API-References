---
title: TiffOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonTiffOptionsaspose.imaging.imageoptions/tiffoptions Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Initialisiert eine neue Instanz von[`TiffOptions`](../../tiffoptions) Klasse.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Das erwartete TIFF-Dateiformat. |
| byteOrder | TiffByteOrder | Die zu verwendende Byte-Reihenfolge des TIFF-Dateiformats. |

### Siehe auch

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Montage [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Initialisiert eine neue Instanz von[`TiffOptions`](../../tiffoptions)Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Das erwartete TIFF-Dateiformat. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie eine Graustufenkopie eines vorhandenen Rahmens erstellen und einem TIFF-Bild hinzufügen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Erstellen Sie eine permanente, nicht temporäre Dateiquelle.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Den aktiven Rahmen mit einem linearen Verlaufspinsel füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Graustufenoptionen
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Erstellen Sie eine Graustufenkopie des aktiven Frames.
    // Die Pixeldaten bleiben erhalten, werden aber in das gewünschte Format konvertiert.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Fügen Sie den neu erstellten Rahmen zum TIFF-Bild hinzu.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

Dieses Beispiel zeigt, wie Sie ein Rasterbild mit verschiedenen Optionen im TIFF-Format speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Setze 8 Bits für jede Farbkomponente.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Lege die Big-Endian-Byte-Reihenfolge fest (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Legen Sie die LZW-Komprimierung fest.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Ermöglicht die Reduzierung der Größe von Halbtonbildern.
// Derzeit wird dieses Feld nur mit LZW-Kodierung verwendet, da LZW wahrscheinlich das einzige TIFF-Kodierungsschema ist
// die erheblich von einem Prädiktorschritt profitiert.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Legen Sie das RGB-Farbmodell fest.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Für YCbCr können Sie eine der folgenden Möglichkeiten verwenden:
// YCbCrSubSampling-Feld JPEG-Sampling-Faktoren
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(Standardwert) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Erstellen Sie einen TIFF-Frame von 100 x 100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Füllen Sie das gesamte Bild mit dem blau-gelben Farbverlauf.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### Siehe auch

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Montage [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Initialisiert eine neue Instanz von[`TiffOptions`](../../tiffoptions) Klasse.

```csharp
public TiffOptions(TiffOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | TiffOptions | Die Optionen zum Kopieren. |

### Siehe auch

* class [TiffOptions](../../tiffoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Montage [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Initialisiert eine neue Instanz von[`TiffOptions`](../../tiffoptions) Klasse.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | TiffDataType[] | Die Tags, mit denen Optionen initialisiert werden sollen. |

### Siehe auch

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
