---
title: Class ImageAttributes
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageAttributes class. An ImageAttributes object contains information about how bitmap and metafile colors are manipulated during rendering. An ImageAttributes object maintains several coloradjustment settings including coloradjustment matrices grayscaleadjustment matrices gammacorrection values colormap tables and colorthreshold values. During rendering colors can be corrected darkened lightened and removed. To apply such manipulations initialize an ImageAttributes object and pass the path of that ImageAttributes object along with the path of an Image to the DrawImage method
type: docs
weight: 9880
url: /net/aspose.imaging/imageattributes/
---
## ImageAttributes class

An `ImageAttributes` object contains information about how bitmap and metafile colors are manipulated during rendering. An `ImageAttributes` object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an `ImageAttributes` object and pass the path of that `ImageAttributes` object (along with the path of an [`Image`](../image/)) to the DrawImage method.

```csharp
public sealed class ImageAttributes
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageAttributes](imageattributes/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable/)() | Clears the brush color-remap table of this `ImageAttributes` object. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey)() | Clears the color key (transparency range) for the default category. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Clears the color key (transparency range) for a specified category. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix)() | Clears the color-adjustment matrix for the default category. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Clears the color-adjustment matrix for a specified category. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma)() | Disables gamma correction for the default category. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Disables gamma correction for a specified category. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop)() | Clears the NoOp setting for the default category. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Clears the NoOp setting for a specified category. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel)() | Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Clears the (cyan-magenta-yellow-black) output channel setting for a specified category. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Clears the output channel color profile setting for the default category. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Clears the output channel color profile setting for a specified category. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable)() | Clears the color-remap table for the default category. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Clears the color-remap table for a specified category. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold)() | Clears the threshold value for the default category. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Clears the threshold value for a specified category. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable/)(ColorMap[]) | Sets the color-remap table for the brush category. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Sets the color key for the default category. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Sets the color key (transparency range) for a specified category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix for a specified category. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma)(float) | Sets the gamma value for the default category. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Sets the gamma value for a specified category. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop)() | Turns off color adjustment for the default category. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Turns off color adjustment for a specified category. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Sets the output channel color-profile file for the default category. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Sets the output channel color-profile file for a specified category. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Sets the color-remap table for the default category. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Sets the color-remap table for a specified category. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold)(float) | Sets the threshold (transparency range) for the default category. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Sets the threshold (transparency range) for a specified category. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


