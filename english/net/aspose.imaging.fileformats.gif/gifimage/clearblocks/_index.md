---
title: GifImage.ClearBlocks
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Clearing all the GIF blocks removes any existing data stored within the image. This operation effectively resets the image to an empty state removing any previously added blocks. Use this method when you need to start fresh with a clean slate for creating or modifying a GIF image
type: docs
weight: 270
url: /net/aspose.imaging.fileformats.gif/gifimage/clearblocks/
---
## GifImage.ClearBlocks method

Clearing all the GIF blocks removes any existing data stored within the image. This operation effectively resets the image to an empty state, removing any previously added blocks. Use this method when you need to start fresh with a clean slate for creating or modifying a GIF image.

```csharp
public void ClearBlocks()
```

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

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


