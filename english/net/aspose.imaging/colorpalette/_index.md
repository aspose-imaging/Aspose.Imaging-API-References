---
title: Class ColorPalette
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ColorPalette class. Defines an array of colors that make up a color palette. The colors are 32bit ARGB colors. Not inheritable
type: docs
weight: 380
url: /net/aspose.imaging/colorpalette/
---
## ColorPalette class

Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Constructors

| Name | Description |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initializes a new instance of the `ColorPalette` class. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initializes a new instance of the `ColorPalette` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32Entries](../../aspose.imaging/colorpalette/argb32entries/) { get; } | Gets an array of 32-bit ARGB structures. |
| [Entries](../../aspose.imaging/colorpalette/entries/) { get; } | Gets an array of [`Color`](../color/) structures. |
| [EntriesCount](../../aspose.imaging/colorpalette/entriescount/) { get; } | Gets the entries count. |
| [IsCompactPalette](../../aspose.imaging/colorpalette/iscompactpalette/) { get; } | Gets or sets a value indicating whether compact palette is used. |

## Methods

| Name | Description |
| --- | --- |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette/#copypalette)(IColorPalette) | Copies the palette. |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copies the palette. |
| [GetArgb32Color](../../aspose.imaging/colorpalette/getargb32color/)(int) | Gets the 32-bit ARGB palette color by index. |
| [GetColor](../../aspose.imaging/colorpalette/getcolor/)(int) | Gets the palette color by index. |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Gets the index of the nearest color. |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Gets the index of the nearest color. |

### See Also

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


