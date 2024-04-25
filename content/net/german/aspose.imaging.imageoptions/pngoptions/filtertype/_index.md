---
title: FilterType
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den beim Speichern der PNG-Datei verwendeten Filtertyp ab oder legt ihn fest.
type: docs
weight: 50
url: /de/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Ruft den beim Speichern der PNG-Datei verwendeten Filtertyp ab oder legt ihn fest.

```csharp
public PngFilterType FilterType { get; set; }
```

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

Das folgende Beispiel zeigt, wie sich verschiedene Filtertypen auf die Größe des ausgegebenen PNG-Bildes auswirken.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Legen Sie einen Filtertyp fest
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//Die Ausgabe könnte so aussehen:
//Der Filtertyp ist None, die Ausgabebildgröße ist 116845 Bytes.
//Der Filtertyp ist Up, die Ausgabebildgröße ist 86360 Byte.
//Der Filtertyp ist Sub, die Ausgabebildgröße ist 94907 Byte.
//Der Filtertyp ist Paeth, die Ausgabebildgröße ist 86403 Byte.
//Der Filtertyp ist Avg, die Ausgabebildgröße ist 89956 Byte.
//Der Filtertyp ist Adaptiv, die Ausgabebildgröße beträgt 97248 Bytes.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../pngoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
