---
title: ImageMask.Union
second_title: Aspose.Imaging for .NET API Reference
description: ImageMask method. Gets the union of the current mask with provided
type: docs
weight: 200
url: /net/aspose.imaging.magicwand.imagemasks/imagemask/union/
---
## Union(ImageMask) {#union}

Gets the union of the current mask with provided.

```csharp
public ImageBitMask Union(ImageMask mask)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mask | ImageMask | Provided mask |

### Return Value

New [`ImageBitMask`](../../imagebitmask/).

## Examples

The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, substract).

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // Create a new mask using magic wand tool based on tone and color of pixel (845, 128)
    MagicWandTool.Select(image, new MagicWandSettings(845, 128))
        // Union the existing mask with the specified one created by magic wand tool
        .Union(new MagicWandSettings(416, 387))
        // Invert the existing mask
        .Invert()
        // Subtract the specified mask created by magic wand tool with specified threshold from the existing one 
        .Subtract(new MagicWandSettings(1482, 346) { Threshold = 69 })
        // Subtract four specified rectangle masks from the existing mask one by one
        .Subtract(new RectangleMask(0, 0, 800, 150))
        .Subtract(new RectangleMask(0, 380, 600, 220))
        .Subtract(new RectangleMask(930, 520, 110, 40))
        .Subtract(new RectangleMask(1370, 400, 120, 200))
        // Feather mask with specified settings
        .GetFeathered(new FeatheringSettings() { Size = 3 })
        // Apply mask to the image
        .Apply();
        
    // Save image
    image.Save(outputFilePath);
}
```

### See Also

* class [ImageBitMask](../../imagebitmask/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Union(MagicWandSettings) {#union_1}

Gets the union of the current mask with the result of magic wand selection applied to the source of the mask.

```csharp
public ImageBitMask Union(MagicWandSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| settings | MagicWandSettings | Magic wand settings. |

### Return Value

New [`ImageBitMask`](../../imagebitmask/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when the source image is not defined in mask. |

### See Also

* class [ImageBitMask](../../imagebitmask/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Union(RasterImage, MagicWandSettings) {#union_2}

Gets the union of the current mask with the result of magic wand selection applied to the provided image.

```csharp
public ImageBitMask Union(RasterImage image, MagicWandSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | Image for magic wand. |
| settings | MagicWandSettings | Magic wand settings. |

### Return Value

New [`ImageBitMask`](../../imagebitmask/).

### See Also

* class [ImageBitMask](../../imagebitmask/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


