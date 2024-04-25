---
title: GifImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avGifImageaspose.imaging.fileformats.gif/gifimage class.
type: docs
weight: 10
url: /sv/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Initierar en ny instans av[`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Den första ramen att initiera gif-bild med. |
| globalPalette | IColorPalette | Den globala paletten att använda. Observera om båda*firstFrame* och*globalPalette* är null används den globala standardpalett. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Ramen kan inte vara null;firstFrame |
| ArgumentException | Den första ramen tillhör redan någon annan bild. Kontrollera egenskapen Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Den angivna paletten bör innehålla antal poster lika med 2 potens. Minimal palettstorlek är 2, maximal är 256. |

### Exempel

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

### Se även

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* hopsättning [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Initierar en ny instans av[`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Den första ramen att initiera gif-bild med. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Ramen kan inte vara null;firstFrame |
| ArgumentException | Den första ramen tillhör redan någon annan bild. Kontrollera egenskapen Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Den angivna paletten bör innehålla antal poster lika med 2 potens. Minimal palettstorlek är 2, maximal är 256. |

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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* hopsättning [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Initierar en ny instans av[`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstFrame | GifFrameBlock | Den första ramen att initiera gif-bild med. |
| globalPalette | IColorPalette | Den globala paletten att använda. Observera om båda*firstFrame* och*globalPalette* är null används den globala standardpalett. |
| isPaletteSorted | Boolean | om inställt på`Sann` paletten är sorterad. Observera att parametern används när*globalPalette* är inte null. |
| paletteColorResolution | Byte | Palettens färgupplösning. Observera att parametern används när*globalPalette* är inte null. |
| paletteBackgroundColorIndex | Byte | Palettens bakgrundsfärgindex. |
| aspectRatio | Byte | Bildförhållandet. |
| hasTrailer | Boolean | om inställt på`Sann` gif-bilden har trailer annars ingen trailer skriven i slutet av streamen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Ramen kan inte vara null;firstFrame |
| ArgumentException | Den första ramen tillhör redan någon annan bild. Kontrollera egenskapen Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | Den angivna paletten bör innehålla antal poster lika med 2 potens. Minimal palettstorlek är 2, maximal är 256. |

### Se även

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
