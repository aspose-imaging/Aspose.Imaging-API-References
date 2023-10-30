---
title: ImageAttributes
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9760
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
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Clears the brush color-remap table of this [`ImageAttributes`](../imageattributes) object. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey)() | Clears the color key (transparency range) for the default category. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey)(ColorAdjustType) | Clears the color key (transparency range) for a specified category. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix)() | Clears the color-adjustment matrix for the default category. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix)(ColorAdjustType) | Clears the color-adjustment matrix for a specified category. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma)() | Disables gamma correction for the default category. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma)(ColorAdjustType) | Disables gamma correction for a specified category. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop)() | Clears the NoOp setting for the default category. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop)(ColorAdjustType) | Clears the NoOp setting for a specified category. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel)() | Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel)(ColorAdjustType) | Clears the (cyan-magenta-yellow-black) output channel setting for a specified category. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile)() | Clears the output channel color profile setting for the default category. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile)(ColorAdjustType) | Clears the output channel color profile setting for a specified category. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable)() | Clears the color-remap table for the default category. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable)(ColorAdjustType) | Clears the color-remap table for a specified category. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold)() | Clears the threshold value for the default category. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold)(ColorAdjustType) | Clears the threshold value for a specified category. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Sets the color-remap table for the brush category. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey)(Color, Color) | Sets the color key for the default category. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey)(Color, Color, ColorAdjustType) | Sets the color key (transparency range) for a specified category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices)(ColorMatrix, ColorMatrix) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix)(ColorMatrix) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix)(ColorMatrix, ColorMatrixFlag) | Sets the color-adjustment matrix for the default category. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix for a specified category. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma)(float) | Sets the gamma value for the default category. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma)(float, ColorAdjustType) | Sets the gamma value for a specified category. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop)() | Turns off color adjustment for the default category. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop)(ColorAdjustType) | Turns off color adjustment for a specified category. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel)(ColorChannelFlag) | Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel)(ColorChannelFlag, ColorAdjustType) | Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile)(string) | Sets the output channel color-profile file for the default category. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile)(string, ColorAdjustType) | Sets the output channel color-profile file for a specified category. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable)(ColorMap[]) | Sets the color-remap table for the default category. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable)(ColorMap[], ColorAdjustType) | Sets the color-remap table for a specified category. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold)(float) | Sets the threshold (transparency range) for the default category. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold)(float, ColorAdjustType) | Sets the threshold (transparency range) for a specified category. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode)(WrapMode) | Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode)(WrapMode, Color) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode)(WrapMode, Color, bool) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
