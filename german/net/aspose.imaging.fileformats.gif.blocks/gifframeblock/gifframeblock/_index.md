---
title: GifFrameBlock
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | UInt16 | Die Bildbreite. |
| height | UInt16 | Die Bildhöhe. |

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

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |
| width | UInt16 | Die Bildbreite. |
| height | UInt16 | Die Bildhöhe. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |
| width | UInt16 | Die Bildbreite. |
| height | UInt16 | Die Bildhöhe. |
| colorPalette | IColorPalette | Die Farbpalette. |
| isPaletteSorted | Boolean | wenn eingestellt`Stimmt` die Farbpalette ist sortiert. |
| isGifFrameInterlaced | Boolean | wenn eingestellt`Stimmt` der GIF-Frame ist interlaced. |
| bitsPerPixel | Byte | Die Bits pro Pixel. |

### Siehe auch

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild, mit dem Bildpixel und Palettendaten initialisiert werden sollen. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild, mit dem Bildpixel und Palettendaten initialisiert werden sollen. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Bild, mit dem Bildpixel und Palettendaten initialisiert werden sollen. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |
| isPaletteSorted | Boolean | wenn eingestellt`Stimmt` die Farbpalette ist sortiert. |
| isGifFrameInterlaced | Boolean | wenn eingestellt`Stimmt` der GIF-Frame ist interlaced. |
| lzwCodeSize | Byte | Die Bits pro Pixel. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem ein Bild geladen und Framepixel- und Palettendaten initialisiert werden sollen. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem ein Bild geladen und Framepixel- und Palettendaten initialisiert werden sollen. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem ein Bild geladen und Framepixel- und Palettendaten initialisiert werden sollen. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |
| isPaletteSorted | Boolean | wenn eingestellt`Stimmt` die Farbpalette ist sortiert. |
| isGifFrameInterlaced | Boolean | wenn eingestellt`Stimmt` der GIF-Frame ist interlaced. |
| lzwCodeSize | Byte | Die Bits pro Pixel. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes und zum Initialisieren von Rahmenpixel- und Palettendaten. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes und zum Initialisieren von Rahmenpixel- und Palettendaten. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Initialisiert eine neue Instanz von[`GifFrameBlock`](../../gifframeblock) Klasse.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden eines Bildes und zum Initialisieren von Rahmenpixel- und Palettendaten. |
| left | UInt16 | Die linke Bildposition. |
| top | UInt16 | Die oberste Bildposition. |
| isPaletteSorted | Boolean | wenn eingestellt`Stimmt` die Farbpalette ist sortiert. |
| isGifFrameInterlaced | Boolean | wenn eingestellt`Stimmt` der GIF-Frame ist interlaced. |
| lzwCodeSize | Byte | Die Bits pro Pixel. |

### Siehe auch

* class [GifFrameBlock](../../gifframeblock)
* namensraum [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
