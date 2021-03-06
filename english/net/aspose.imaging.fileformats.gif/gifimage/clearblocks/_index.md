---
title: ClearBlocks
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 290
url: /net/aspose.imaging.fileformats.gif/gifimage/clearblocks/
---
## GifImage.ClearBlocks method

Clears all the GIF blocks.

```csharp
public void ClearBlocks()
```

### Examples

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

* class [GifImage](../../gifimage)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
