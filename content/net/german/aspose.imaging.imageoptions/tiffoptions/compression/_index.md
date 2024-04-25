---
title: Compression
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Komprimierung ab oder legt sie fest.
type: docs
weight: 90
url: /de/aspose.imaging.imageoptions/tiffoptions/compression/
---
## TiffOptions.Compression property

Ruft die Komprimierung ab oder legt sie fest.

```csharp
public TiffCompressions Compression { get; set; }
```

### Eigentumswert

Die Komprimierung.

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

* enum [TiffCompressions](../../../aspose.imaging.fileformats.tiff.enums/tiffcompressions)
* class [TiffOptions](../../tiffoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
