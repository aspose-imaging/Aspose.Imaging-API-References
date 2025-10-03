---
title: GifImage.AddBlock
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Adding a new GIF block allows you to include additional data within the image. This method enables you to append custom blocks to the GIF image which can contain various types of information
type: docs
weight: 190
url: /net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

Adding a new GIF block allows you to include additional data within the image. This method enables you to append custom blocks to the GIF image, which can contain various types of information.

```csharp
public void AddBlock(IGifBlock block)
```

| Parameter | Type | Description |
| --- | --- | --- |
| block | IGifBlock | The GIF block to add. |

## Examples

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

* interface [IGifBlock](../../igifblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


