---
title: ActiveFrame
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in den aktiva ramen.
type: docs
weight: 20
url: /sv/net/aspose.imaging.fileformats.gif/gifimage/activeframe/
---
## GifImage.ActiveFrame property

Hämtar eller ställer in den aktiva ramen.

```csharp
public GifFrameBlock ActiveFrame { get; set; }
```

### Fastighetsvärde

Den aktiva ramen.

### Exempel

Följande exempel visar hur man tar bort alla block från en GIF-bild.

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

// Utgången ser ut så här:
// Aktiv ramstorlek: { Width = 100, Height = 100}
// Rensa alla block
// Aktiv bildruta är inte inställd
```

### Se även

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
