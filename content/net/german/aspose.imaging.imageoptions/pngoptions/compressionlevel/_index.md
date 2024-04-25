---
title: CompressionLevel
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die PNG-Bildkomprimierungsstufe im Bereich von 0 bis 9 wobei 9 die maximale Komprimierung und 0 der Speichermodus ist.
type: docs
weight: 40
url: /de/aspose.imaging.imageoptions/pngoptions/compressionlevel/
---
## PngOptions.CompressionLevel property

Die PNG-Bildkomprimierungsstufe im Bereich von 0 bis 9, wobei 9 die maximale Komprimierung und 0 der Speichermodus ist.

```csharp
public int CompressionLevel { get; set; }
```

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

Das folgende Beispiel zeigt, wie Sie ein Bild mit verschiedenen Optionen im PNG-Format speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 x 100 Pixel.
// Sie können auch Bilder in jedem unterstützten Format aus einer Datei oder einem Stream laden.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Füllen Sie das Bild mit dem blau-transparenten Farbverlauf.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Progressives Laden.
    saveOptions.Progressive = true;

    // Legen Sie die horizontale und vertikale Auflösung auf 96 Pixel pro Zoll fest.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Jedes Pixel ist ein (rot, grün, blau) Tripel gefolgt von Alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Legen Sie die maximale Komprimierungsstufe fest.
    saveOptions.CompressionLevel = 9;

    // Dies ist die beste Komprimierung, aber die langsamste Ausführungszeit.
    // Adaptive Filterung bedeutet, dass der Speicherprozess den geeignetsten Filter für jede Datenzeile auswählt.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Die Anzahl der Bits pro Kanal.
    saveOptions.BitDepth = 8;

    // In einer Datei speichern.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Siehe auch

* class [PngOptions](../../pngoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../pngoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
