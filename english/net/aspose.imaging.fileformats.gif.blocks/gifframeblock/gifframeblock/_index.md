---
title: GifFrameBlock.GifFrameBlock
second_title: Aspose.Imaging for .NET API Reference
description: GifFrameBlock constructor. Initializes a new instance of the GifFrameBlock class
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | UInt16 | The image width. |
| height | UInt16 | The image height. |

## Examples

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

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |
| width | UInt16 | The image width. |
| height | UInt16 | The image height. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |
| width | UInt16 | The image Width. |
| height | UInt16 | The image Height. |
| colorPalette | IColorPalette | The color palette. |
| isPaletteSorted | Boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | Boolean | if set to `true` the GIF frame is interlaced. |
| bitsPerPixel | Byte | The bits per pixel. |

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(RasterImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image to initialize frame pixel and palette data with. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image to initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image to initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |
| isPaletteSorted | Boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | Boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | Byte | The bits per pixel. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image from and initialize frame pixel and palette data with. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image from and initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image from and initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |
| isPaletteSorted | Boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | Boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | Byte | The bits per pixel. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image from and initialize frame pixel and palette data with. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image from and initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

Initializes a new instance of the [`GifFrameBlock`](../) class.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image from and initialize frame pixel and palette data with. |
| left | UInt16 | The left image position. |
| top | UInt16 | The top image position. |
| isPaletteSorted | Boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | Boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | Byte | The bits per pixel. |

### See Also

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)


