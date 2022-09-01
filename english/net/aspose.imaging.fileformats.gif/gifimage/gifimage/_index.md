---
title: GifImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage constructor (1 of 3)

Initializes a new instance of the [`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | The first frame to initialize gif image with. |
| globalPalette | IColorPalette | The global palette to use. Note if both *firstFrame* and *globalPalette* are null then default global palette is used. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The *firstFrame* cannot be null |
| ArgumentException | The *firstFrame* already belongs to some other image. Check the Container property. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | The *globalPalette* specified should contain entries count equal to power of 2. Minimal palette size is 2, maximal is 256. |

### Examples

This example shows how to create a GIF image with a custom palette and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF Frame block of 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fill the entire block in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // Use 4-bit palette to reduce the image size. The quality can get worse.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### See Also

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assembly [Aspose.Imaging](../../../)

---

## GifImage constructor (2 of 3)

Initializes a new instance of the [`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | The first frame to initialize gif image with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The *firstFrame* cannot be null |
| ArgumentException | The *firstFrame* already belongs to some other image. Check the Container property. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | The palette specified must contain entries count equal to power of 2. Minimal palette size is 2, maximal is 256. |

### Examples

This example shows how to create a GIF image and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF Frame block of 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fill the entire block in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

The following example shows how to compose an animated GIF image from individual GIF blocks.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF image 100 x 100 px.
// The first block is fully black by default.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // The first circle is red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // The second circle is black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Gradually inscrease the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Gradually inscrease the angle of the black arc and wipe out the red arc.
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

### See Also

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assembly [Aspose.Imaging](../../../)

---

## GifImage constructor (3 of 3)

Initializes a new instance of the [`GifImage`](../../gifimage) class.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | The first frame to initialize gif image with. |
| globalPalette | IColorPalette | The global palette to use. Note if both *firstFrame* and *globalPalette* are null then default global palette is used. |
| isPaletteSorted | Boolean | if set to `true` the palette is sorted. Note the parameter is used when *globalPalette* is not null. |
| paletteColorResolution | Byte | The palette color resolution. Note the parameter is used when *globalPalette* is not null. |
| paletteBackgroundColorIndex | Byte | The palette background color index. |
| aspectRatio | Byte | The aspect ratio. |
| hasTrailer | Boolean | if set to `true` the gif image has trailer otherwise no trailer written at the end of the stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The *firstFrame* cannot be null |
| ArgumentException | The *firstFrame* already belongs to some other image. Check the Container property. |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | The *globalPalette* specified should contain entries count equal to power of 2. Minimal palette size is 2, maximal is 256. |

### See Also

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
