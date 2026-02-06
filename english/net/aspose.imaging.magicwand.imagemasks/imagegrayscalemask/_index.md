---
title: Class ImageGrayscaleMask
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.MagicWand.ImageMasks.ImageGrayscaleMask class. Describes a grayscale image mask
type: docs
weight: 10870
url: /net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
## ImageGrayscaleMask class

Describes a grayscale image mask.

```csharp
public class ImageGrayscaleMask : IImageMask
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor)(RasterImage) | Initializes a new instance of the `ImageGrayscaleMask` class with the size of the specified existing [`RasterImage`](../../aspose.imaging/rasterimage/). Specified [`RasterImage`](../../aspose.imaging/rasterimage/) will be stored as source image. |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor_1)(int, int) | Initializes a new instance of the `ImageGrayscaleMask` class with the specified width and height. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/bounds/) { get; } | Gets the bounds, in pixels, of this mask. |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/height/) { get; } | Gets the height, in pixels, of this mask. |
| [Item](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/item/) { get; set; } | Gets or sets the opacity of the specified pixel. |
| [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/selectionbounds/) { get; } | Gets the bounds of the selected part of the mask, in pixels. |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/source/) { get; } | Gets the source image used to create this mask, if exists. |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/width/) { get; } | Gets the width, in pixels, of this mask. |

## Methods

| Name | Description |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/apply/)() | Applies current mask to the [`RasterImage`](../../aspose.imaging/rasterimage/) source, if exists. |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/applyto/)(RasterImage) | Applies current mask to the specified [`RasterImage`](../../aspose.imaging/rasterimage/). |
| [Clone](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/clone/)() | Creates a new object that is a copy of the current instance. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop)(Rectangle) | Crops mask with the specified rectangle. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_1)(Size) | Crops mask with the specified size. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_2)(int, int) | Crops mask with the specified width and height. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/exclusivedisjunction/)(ImageGrayscaleMask) | Gets the exclusive disjunction of current mask with provided. |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/getbyteopacity/)(int, int) | Gets the opacity of the specified pixel with byte precision. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/intersect/)(ImageGrayscaleMask) | Gets the intersection of current mask with provided. |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/invert/)() | Gets the inversion of the current mask. |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/isopaque/)(int, int) | Checks if the specified pixel is opaque. |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/istransparent/)(int, int) | Checks if the specified pixel is transparent. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/subtract/)(ImageGrayscaleMask) | Gets the subtraction of the provided mask from current. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/union/)(ImageGrayscaleMask) | Union of two masks. |
| [operator +](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_addition/) | Union of two masks. |
| [operator ^](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_exclusiveor/) | Exclusive disjunction of two masks. |
| [operator !](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_logicalnot/) | Inverts mask. |
| [operator *](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_multiply/) | Intersection of two masks. |
| [operator -](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_subtraction/) | Subtract second mask from first. |

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

* interface [IImageMask](../iimagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


