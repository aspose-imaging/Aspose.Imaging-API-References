---
title: ImageAttributes Class
type: docs
weight: 510
url: /python-net/aspose.imaging/imageattributes/
---

An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.ImageAttributes

**Assembly:**  Aspose.Imaging Version: 23.6.0

The ImageAttributes type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|ImageAttributes()|Initializes a new instance of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|set_color_matrix(new_color_matrix)|Sets the color-adjustment matrix for the default category.|
|set_color_matrix(new_color_matrix, flags)|Sets the color-adjustment matrix for the default category.|
|set_color_matrix(new_color_matrix, mode, type)|Sets the color-adjustment matrix for a specified category.|
|clear_color_matrix()|Clears the color-adjustment matrix for the default category.|
|clear_color_matrix(type)|Clears the color-adjustment matrix for a specified category.|
|set_color_matrices(new_color_matrix, gray_matrix)|Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.|
|set_color_matrices(new_color_matrix, gray_matrix, flags)|Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.|
|set_color_matrices(new_color_matrix, gray_matrix, mode, type)|Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category.|
|set_threshold(threshold)|Sets the threshold (transparency range) for the default category.|
|set_threshold(threshold, type)|Sets the threshold (transparency range) for a specified category.|
|clear_threshold()|Clears the threshold value for the default category.|
|clear_threshold(type)|Clears the threshold value for a specified category.|
|set_gamma(gamma)|Sets the gamma value for the default category.|
|set_gamma(gamma, type)|Sets the gamma value for a specified category.|
|clear_gamma()|Disables gamma correction for the default category.|
|clear_gamma(type)|Disables gamma correction for a specified category.|
|set_no_op()|Turns off color adjustment for the default category.|
|set_no_op(type)|Turns off color adjustment for a specified category.|
|clear_no_op()|Clears the NoOp setting for the default category.|
|clear_no_op(type)|Clears the NoOp setting for a specified category.|
|set_color_key(color_low, color_high)|Sets the color key for the default category.|
|set_color_key(color_low, color_high, type)|Sets the color key (transparency range) for a specified category.|
|clear_color_key()|Clears the color key (transparency range) for the default category.|
|clear_color_key(type)|Clears the color key (transparency range) for a specified category.|
|set_output_channel(flags)|Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category.|
|set_output_channel(flags, type)|Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category.|
|clear_output_channel()|Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category.|
|clear_output_channel(type)|Clears the (cyan-magenta-yellow-black) output channel setting for a specified category.|
|set_output_channel_color_profile(color_profile_filename)|Sets the output channel color-profile file for the default category.|
|set_output_channel_color_profile(color_profile_filename, type)|Sets the output channel color-profile file for a specified category.|
|clear_output_channel_color_profile()|Clears the output channel color profile setting for the default category.|
|clear_output_channel_color_profile(type)|Clears the output channel color profile setting for a specified category.|
|set_remap_table(map)|Sets the color-remap table for the default category.|
|set_remap_table(map, type)|Sets the color-remap table for a specified category.|
|clear_remap_table()|Clears the color-remap table for the default category.|
|clear_remap_table(type)|Clears the color-remap table for a specified category.|
|set_wrap_mode(mode)|Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.|
|set_wrap_mode(mode, color)|Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.|
|set_wrap_mode(mode, color, clamp)|Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.|
|set_brush_remap_table(map)|Sets the color-remap table for the brush category.|
|clear_brush_remap_table()|Clears the brush color-remap table of this [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object.|
