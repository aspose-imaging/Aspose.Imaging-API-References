---
title: GifFrameBlock
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avGifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | UInt16 | Bildens bredd. |
| height | UInt16 | Bildhöjden. |

### Exempel

Det här exemplet visar hur man skapar en GIF-bild och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa ett GIF-ramblock på 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fyll hela blocket med rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Det här exemplet visar hur man skapar en GIF-bild med en anpassad palett och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa ett GIF-ramblock på 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fyll hela blocket med rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Använd 4-bitars palett för att minska bildstorleken. Kvaliteten kan bli sämre.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Följande exempel visar hur man komponerar en animerad GIF-bild från enskilda GIF-block.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en GIF-bild 100 x 100 px.
// Det första blocket är helt svart som standard.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Den första cirkeln är röd
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Den andra cirkeln är svart
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Öka gradvis vinkeln på den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Öka gradvis vinkeln på den svarta bågen och torka ut den röda bågen.
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

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |
| width | UInt16 | Bildens bredd. |
| height | UInt16 | Bildhöjden. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |
| width | UInt16 | Bildens bredd. |
| height | UInt16 | Bilden Höjd. |
| colorPalette | IColorPalette | Färgpaletten. |
| isPaletteSorted | Boolean | om inställt på`Sann` färgpaletten är sorterad. |
| isGifFrameInterlaced | Boolean | om inställt på`Sann` GIF-ramen är sammanflätad. |
| bitsPerPixel | Byte | Bitarna per pixel. |

### Se även

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden att initiera rampixel och palettdata med. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden att initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden att initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |
| isPaletteSorted | Boolean | om inställt på`Sann` färgpaletten är sorterad. |
| isGifFrameInterlaced | Boolean | om inställt på`Sann` GIF-ramen är sammanflätad. |
| lzwCodeSize | Byte | Bitarna per pixel. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda en bild från och initiera rampixel och palettdata med. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda en bild från och initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda en bild från och initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |
| isPaletteSorted | Boolean | om inställt på`Sann` färgpaletten är sorterad. |
| isGifFrameInterlaced | Boolean | om inställt på`Sann` GIF-ramen är sammanflätad. |
| lzwCodeSize | Byte | Bitarna per pixel. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild från och initiera rampixel och palettdata med. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild från och initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Initierar en ny instans av[`GifFrameBlock`](../../gifframeblock) class.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild från och initiera rampixel och palettdata med. |
| left | UInt16 | Den vänstra bildens position. |
| top | UInt16 | Den översta bildens position. |
| isPaletteSorted | Boolean | om inställt på`Sann` färgpaletten är sorterad. |
| isGifFrameInterlaced | Boolean | om inställt på`Sann` GIF-ramen är sammanflätad. |
| lzwCodeSize | Byte | Bitarna per pixel. |

### Se även

* class [GifFrameBlock](../../gifframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
