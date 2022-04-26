---
title: GifFrameBlock
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 6590
url: /net/aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
## GifFrameBlock class

Gif frame block.

```csharp
public sealed class GifFrameBlock : RasterCachedImage, IAnimationFrame, IGifBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [GifFrameBlock](gifframeblock)(RasterImage) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(Stream) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(string) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(ushort, ushort) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(RasterImage, ushort, ushort) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(Stream, ushort, ushort) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(string, ushort, ushort) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(ushort, ushort, ushort, ushort) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(RasterImage, ushort, ushort, bool, bool, byte) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(Stream, ushort, ushort, bool, bool, byte) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(string, ushort, ushort, bool, bool, byte) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |
| [GifFrameBlock](gifframeblock)(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) | Initializes a new instance of the [`GifFrameBlock`](../gifframeblock) class. |

## Properties

| Name | Description |
| --- | --- |
| override [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [ControlBlock](controlblock) { get; } | Gets the graphics control block associated with this block. |
| [DisposalMethod](disposalmethod) { get; } | Gets the disposal method. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [Flags](flags) { get; set; } | Gets or sets the flags. |
| [FrameLeft](frameleft) { get; } | Gets the left. |
| [FrameTime](frametime) { get; set; } | Gets or sets the duration. |
| [FrameTop](frametop) { get; } | Converts to p. |
| [GifFrameBitsPerPixel](gifframebitsperpixel) { get; set; } | Gets or sets the GIF frame bits per pixel. |
| override [HasTransparentColor](hastransparentcolor) { get; set; } | Gets a value indicating whether frame block has transparent color. |
| override [Height](height) { get; } | Gets the image height. |
| [Interlaced](interlaced) { get; set; } | Gets or sets a value indicating whether this [`GifFrameBlock`](../gifframeblock) is interlaced. |
| [IsInterlaced](isinterlaced) { get; } | Gets a value indicating whether this image instance is interlaced. |
| [IsPaletteSorted](ispalettesorted) { get; set; } | Gets or sets a value indicating whether color palette is sorted. |
| [Left](left) { get; set; } | Gets or sets the left image location. |
| [Top](top) { get; set; } | Gets or sets the top image location. |
| override [TransparentColor](transparentcolor) { get; set; } | Gets the transparent color of frame block. |
| override [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a brightness for image. |
| [GetFullFrame](getfullframe)() | Gets the full frame. |
| override [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [ReplaceColor](replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceNonTransparentColors](replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| static [CreateFlags](createflags)(IColorPalette, bool, bool) | Creates the flags. |
| static [GetColorPalette](getcolorpalette)(IColorPalette, IColorPalette) | Gets the associated color palette. |

## Other Members

| Name | Description |
| --- | --- |
| const [ExtensionLabel](extensionlabel) | Block extension label. |
| const [ImageDescriptorSize](imagedescriptorsize) | The image descriptor size. |

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* interface [IAnimationFrame](../../aspose.imaging/ianimationframe)
* interface [IGifBlock](../../aspose.imaging.fileformats.gif/igifblock)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
