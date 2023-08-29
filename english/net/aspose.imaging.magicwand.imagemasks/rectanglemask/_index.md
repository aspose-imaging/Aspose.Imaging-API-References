---
title: RectangleMask
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10640
url: /net/aspose.imaging.magicwand.imagemasks/rectanglemask/
---
## RectangleMask class

Describes a rectangle mask.

```csharp
public class RectangleMask : ImageMask
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleMask](rectanglemask)(Rectangle) | Initializes a new instance of the [`RectangleMask`](../rectanglemask) class with the specified rectangle. |
| [RectangleMask](rectanglemask)(int, int, int, int) | Initializes a new instance of the [`RectangleMask`](../rectanglemask) class with the specified left-top point, width and height. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds) { get; } | Gets the bounds, in pixels, of this mask. |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height) { get; } | Gets the height, in pixels, of this mask. |
| override [Item](../../aspose.imaging.magicwand.imagemasks/rectanglemask/item) { get; } | Gets the opacity of the specified pixel. |
| override [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/rectanglemask/selectionbounds) { get; } | Gets the bounds of the selected part of the mask, in pixels. |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source) { get; } | Gets the source image used to create this mask, if exists. |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width) { get; } | Gets the width, in pixels, of this mask. |

## Methods

| Name | Description |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply)() | Applies current mask to the [`RasterImage`](../../aspose.imaging/rasterimage) source, if exists. |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto)(RasterImage) | Applies current mask to the specified [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [Clone](../../aspose.imaging.magicwand.imagemasks/rectanglemask/clone)() | Creates a new object that is a copy of the current instance. |
| override [Crop](../../aspose.imaging.magicwand.imagemasks/rectanglemask/crop)(Rectangle) | Crops mask with the specified rectangle. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop)(Size) | Crops mask with the specified size. |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop)(int, int) | Crops mask with the specified width and height. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction)(ImageMask) | Gets the exclusive disjunction of current mask with provided. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction)(MagicWandSettings) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask. |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction)(RasterImage, MagicWandSettings) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image. |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity)(int, int) | Gets the opacity of the specified pixel with byte precision. |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered)(FeatheringSettings) | Gets grayscale mask with the border feathered with the specified settings. |
| override [Inflate](../../aspose.imaging.magicwand.imagemasks/rectanglemask/inflate)(int) | Inflates this mask by the specified amount. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect)(ImageMask) | Gets the intersection of current mask with provided. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect)(MagicWandSettings) | Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask. |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect)(RasterImage, MagicWandSettings) | Gets the intersection of the current mask with the result of magic wand selection applied to the provided image. |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagemask/invert)() | Gets the inversion of the current mask. |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagemask/isopaque)(int, int) | Checks if the specified pixel is opaque. |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagemask/istransparent)(int, int) | Checks if the specified pixel is transparent. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract)(ImageMask) | Gets the subtraction of the provided mask from current. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract)(MagicWandSettings) | Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask. |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract)(RasterImage, MagicWandSettings) | Gets the result of magic wand selection applied to the provided image subtracted from the current mask. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union)(ImageMask) | Gets the union of the current mask with provided. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union)(MagicWandSettings) | Gets the union of the current mask with the result of magic wand selection applied to the source of the mask. |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union)(RasterImage, MagicWandSettings) | Gets the union of the current mask with the result of magic wand selection applied to the provided image. |

### See Also

* class [ImageMask](../imagemask)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->