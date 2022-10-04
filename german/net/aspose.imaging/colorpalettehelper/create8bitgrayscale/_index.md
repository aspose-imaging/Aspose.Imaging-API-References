---
title: Create8BitGrayscale
second_title: Aspose.Imaging für .NET-API-Referenz
description: Erstellt die 8-Bit-Graustufenpalette.
type: docs
weight: 40
url: /de/net/aspose.imaging/colorpalettehelper/create8bitgrayscale/
---
## ColorPaletteHelper.Create8BitGrayscale method

Erstellt die 8-Bit-Graustufenpalette.

```csharp
public static IColorPalette Create8BitGrayscale(bool minIsWhite)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minIsWhite | Boolean | wenn eingestellt`Stimmt` Die Palette beginnt mit weißer Farbe, ansonsten mit schwarzer Farbe. |

### Rückgabewert

Die 8-Bit-Graustufenpalette.

### Beispiele

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

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->