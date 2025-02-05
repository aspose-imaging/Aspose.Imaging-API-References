---
title: Class ColorPaletteHelper
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ColorPaletteHelper class. Helper class for color palettes manipulation
type: docs
weight: 390
url: /net/aspose.imaging/colorpalettehelper/
---
## ColorPaletteHelper class

Helper class for color palettes manipulation.

```csharp
public static class ColorPaletteHelper
```

## Methods

| Name | Description |
| --- | --- |
| static [Create4Bit](../../aspose.imaging/colorpalettehelper/create4bit/)() | Creates the 4 bit color palette. |
| static [Create4BitGrayscale](../../aspose.imaging/colorpalettehelper/create4bitgrayscale/)(bool) | Creates the 4 bit grayscale palette. |
| static [Create8Bit](../../aspose.imaging/colorpalettehelper/create8bit/)() | Creates the 8 bit color palette. |
| static [Create8BitGrayscale](../../aspose.imaging/colorpalettehelper/create8bitgrayscale/)(bool) | Creates the 8 bit grayscale palette. |
| static [CreateGrayscale](../../aspose.imaging/colorpalettehelper/creategrayscale/)(int) | Gets the grayscale palette of specified bit count. Allowed bit values are 1, 2, 4, 8. |
| static [CreateMonochrome](../../aspose.imaging/colorpalettehelper/createmonochrome/)() | Creates a monochrome color palette containing 2 colors only. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_4)(RasterImage, int) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_5)(RasterImage, int, PaletteMiningMethod) | Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette)(RasterImage, Rectangle, int) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_1)(RasterImage, Rectangle, int, bool) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_2)(RasterImage, Rectangle, int, bool, Color) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_3)(RasterImage, Rectangle, int, bool, Color, bool) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetCloseTransparentImagePalette](../../aspose.imaging/colorpalettehelper/getclosetransparentimagepalette/)(RasterImage, int) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| static [GetDownscalePalette](../../aspose.imaging/colorpalettehelper/getdownscalepalette/)(RasterImage) | Get 256 color palette, composed from upper bits of initial image color values. |
| static [GetUniformColorPalette](../../aspose.imaging/colorpalettehelper/getuniformcolorpalette/)(RasterImage) | Get uniform 256 color palette. |
| static [HasTransparentColors](../../aspose.imaging/colorpalettehelper/hastransparentcolors/)(IColorPalette) | Determines whether the specified palette has transparent colors. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


