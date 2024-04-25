---
title: GifImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonGifImageaspose.imaging.fileformats.gif/gifimage Klasse.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Initialisiert eine neue Instanz von[`GifImage`](../../gifimage) Klasse.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Der erste Frame, mit dem das GIF-Bild initialisiert wird. |
| globalPalette | IColorPalette | Die zu verwendende globale Palette. Beachten Sie, ob beides*firstFrame* und*globalPalette* Null sind, wird die globale Standardpalette verwendet. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Der Frame darf nicht null;firstFrame sein |
| ArgumentException | Das erste Bild gehört bereits zu einem anderen Bild. Überprüfen Sie die Container-Eigenschaft.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Die angegebene Palette sollte Einträge enthalten, die der Potenz von 2 entsprechen. Die minimale Palettengröße beträgt 2, die maximale 256. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein GIF-Bild mit einer benutzerdefinierten Palette erstellen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie einen GIF-Frame-Block von 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Den gesamten Block rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Verwenden Sie die 4-Bit-Palette, um die Bildgröße zu reduzieren. Die Qualität kann schlechter werden.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### Siehe auch

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namensraum [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Montage [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Initialisiert eine neue Instanz von[`GifImage`](../../gifimage) Klasse.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Der erste Frame, mit dem das GIF-Bild initialisiert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Der Frame darf nicht null;firstFrame sein |
| ArgumentException | Das erste Bild gehört bereits zu einem anderen Bild. Überprüfen Sie die Container-Eigenschaft.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Die angegebene Palette sollte Einträge enthalten, die der Potenz von 2 entsprechen. Die minimale Palettengröße beträgt 2, die maximale 256. |

### Beispiele

Dieses Beispiel zeigt, wie ein GIF-Bild erstellt und in einer Datei gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie einen GIF-Frame-Block von 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Den gesamten Block rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Das folgende Beispiel zeigt, wie Sie aus einzelnen GIF-Blöcken ein animiertes GIF-Bild zusammenstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein GIF-Bild 100 x 100 px.
// Der erste Block ist standardmäßig komplett schwarz.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Der erste Kreis ist rot
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Der zweite Kreis ist schwarz
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Erhöhen Sie allmählich den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Erhöhen Sie allmählich den Winkel des schwarzen Bogens und löschen Sie den roten Bogen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Siehe auch

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* namensraum [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Montage [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Initialisiert eine neue Instanz von[`GifImage`](../../gifimage) Klasse.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Der erste Frame, mit dem das GIF-Bild initialisiert wird. |
| globalPalette | IColorPalette | Die zu verwendende globale Palette. Beachten Sie, ob beides*firstFrame* und*globalPalette* Null sind, wird die globale Standardpalette verwendet. |
| isPaletteSorted | Boolean | wenn eingestellt`Stimmt` Die Palette ist sortiert. Beachten Sie, dass der Parameter wann verwendet wird*globalPalette* ist nicht null. |
| paletteColorResolution | Byte | Die Farbauflösung der Palette. Beachten Sie, dass der Parameter wann verwendet wird*globalPalette* ist nicht null. |
| paletteBackgroundColorIndex | Byte | Der Index der Hintergrundfarbe der Palette. |
| aspectRatio | Byte | Das Seitenverhältnis. |
| hasTrailer | Boolean | wenn eingestellt`Stimmt` Das GIF-Bild hat einen Trailer, ansonsten wird kein Trailer am Ende des Streams geschrieben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Der Frame darf nicht null;firstFrame sein |
| ArgumentException | Das erste Bild gehört bereits zu einem anderen Bild. Überprüfen Sie die Container-Eigenschaft.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Die angegebene Palette sollte Einträge enthalten, die der Potenz von 2 entsprechen. Die minimale Palettengröße beträgt 2, die maximale 256. |

### Siehe auch

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namensraum [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
