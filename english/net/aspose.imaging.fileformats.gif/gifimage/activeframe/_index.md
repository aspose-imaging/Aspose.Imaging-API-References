---
title: GifImage.ActiveFrame
second_title: Aspose.Imaging for .NET API Reference
description: GifImage property. Manage and manipulate frames with this property enabling smooth navigation and modification of the active frame within the GIF image
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.gif/gifimage/activeframe/
---
## GifImage.ActiveFrame property

Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image.

```csharp
public GifFrameBlock ActiveFrame { get; set; }
```

### Property Value

The active frame.

## Examples

The following example shows how to remove all blocks from a GIF image.

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }

    System.Console.WriteLine("Clear all the blocks");
    gifImage.ClearBlocks();

    if (gifImage.ActiveFrame != null)
    {
        System.Console.WriteLine("Active frame size: {0}", gifImage.ActiveFrame.Size);
    }
    else
    {
        System.Console.WriteLine("Active frame is not set");
    }
}

// The output looks like this:
// Active frame size: { Width = 100, Height = 100}
// Clear all the blocks
// Active frame is not set
```

### See Also

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


