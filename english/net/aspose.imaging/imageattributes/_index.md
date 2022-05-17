---
title: ImageAttributes
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9670
url: /net/aspose.imaging/imageattributes/
---
## ImageAttributes class

An [`ImageAttributes`](../imageattributes) object contains information about how bitmap and metafile colors are manipulated during rendering. An [`ImageAttributes`](../imageattributes) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [`ImageAttributes`](../imageattributes) object and pass the path of that [`ImageAttributes`](../imageattributes) object (along with the path of an [`Image`](../image)) to the DrawImage method.

```csharp
public sealed class ImageAttributes
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageAttributes](imageattributes)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBrushRemapTable](clearbrushremaptable)() | Clears the brush color-remap table of this [`ImageAttributes`](../imageattributes) object. |
| [ClearColorKey](clearcolorkey)() | Clears the color key (transparency range) for the default category. |
| [ClearColorKey](clearcolorkey)(ColorAdjustType) | Clears the color key (transparency range) for a specified category. |
| [ClearColorMatrix](clearcolormatrix)() | Clears the color-adjustment matrix for the default category. |
| [ClearColorMatrix](clearcolormatrix)(ColorAdjustType) | Clears the color-adjustment matrix for a specified category. |
| [ClearGamma](cleargamma)() | Disables gamma correction for the default category. |
| [ClearGamma](cleargamma)(ColorAdjustType) | Disables gamma correction for a specified category. |
| [ClearNoOp](clearnoop)() | Clears the NoOp setting for the default category. |
| [ClearNoOp](clearnoop)(ColorAdjustType) | Clears the NoOp setting for a specified category. |
| [ClearOutputChannel](clearoutputchannel)() | Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category. |
| [ClearOutputChannel](clearoutputchannel)(ColorAdjustType) | Clears the (cyan-magenta-yellow-black) output channel setting for a specified category. |
| [ClearOutputChannelColorProfile](clearoutputchannelcolorprofile)() | Clears the output channel color profile setting for the default category. |
| [ClearOutputChannelColorProfile](clearoutputchannelcolorprofile)(ColorAdjustType) | Clears the output channel color profile setting for a specified category. |
| [ClearRemapTable](clearremaptable)() | Clears the color-remap table for the default category. |
| [ClearRemapTable](clearremaptable)(ColorAdjustType) | Clears the color-remap table for a specified category. |
| [ClearThreshold](clearthreshold)() | Clears the threshold value for the default category. |
| [ClearThreshold](clearthreshold)(ColorAdjustType) | Clears the threshold value for a specified category. |
| [SetBrushRemapTable](setbrushremaptable)(ColorMap[]) | Sets the color-remap table for the brush category. |
| [SetColorKey](setcolorkey)(Color, Color) | Sets the color key for the default category. |
| [SetColorKey](setcolorkey)(Color, Color, ColorAdjustType) | Sets the color key (transparency range) for a specified category. |
| [SetColorMatrices](setcolormatrices)(ColorMatrix, ColorMatrix) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](setcolormatrices)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](setcolormatrices)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category. |
| [SetColorMatrix](setcolormatrix)(ColorMatrix) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](setcolormatrix)(ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](setcolormatrix)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix for a specified category. |
| [SetGamma](setgamma)(float) | Sets the gamma value for the default category. |
| [SetGamma](setgamma)(float, ColorAdjustType) | Sets the gamma value for a specified category. |
| [SetNoOp](setnoop)() | Turns off color adjustment for the default category. |
| [SetNoOp](setnoop)(ColorAdjustType) | Turns off color adjustment for a specified category. |
| [SetOutputChannel](setoutputchannel)(ColorChannelFlag) | Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category. |
| [SetOutputChannel](setoutputchannel)(ColorChannelFlag, ColorAdjustType) | Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category. |
| [SetOutputChannelColorProfile](setoutputchannelcolorprofile)(string) | Sets the output channel color-profile file for the default category. |
| [SetOutputChannelColorProfile](setoutputchannelcolorprofile)(string, ColorAdjustType) | Sets the output channel color-profile file for a specified category. |
| [SetRemapTable](setremaptable)(ColorMap[]) | Sets the color-remap table for the default category. |
| [SetRemapTable](setremaptable)(ColorMap[], ColorAdjustType) | Sets the color-remap table for a specified category. |
| [SetThreshold](setthreshold)(float) | Sets the threshold (transparency range) for the default category. |
| [SetThreshold](setthreshold)(float, ColorAdjustType) | Sets the threshold (transparency range) for a specified category. |
| [SetWrapMode](setwrapmode)(WrapMode) | Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](setwrapmode)(WrapMode, Color) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](setwrapmode)(WrapMode, Color, bool) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
