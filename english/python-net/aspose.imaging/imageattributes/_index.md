---
title: ImageAttributes Class
type: docs
weight: 5660
url: /python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initializes a new instance of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_brush_remap_table() | Clears the brush color-remap table of this [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object. |
| clear_color_key() | Clears the color key (transparency range) for the default category. |
| [clear_color_key(type)](#clear_color_key_type_1) | Clears the color key (transparency range) for a specified category. |
| clear_color_matrix() | Clears the color-adjustment matrix for the default category. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Clears the color-adjustment matrix for a specified category. |
| clear_gamma() | Disables gamma correction for the default category. |
| [clear_gamma(type)](#clear_gamma_type_3) | Disables gamma correction for a specified category. |
| clear_no_op() | Clears the NoOp setting for the default category. |
| [clear_no_op(type)](#clear_no_op_type_4) | Clears the NoOp setting for a specified category. |
| clear_output_channel() | Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Clears the (cyan-magenta-yellow-black) output channel setting for a specified category. |
| clear_output_channel_color_profile() | Clears the output channel color profile setting for the default category. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Clears the output channel color profile setting for a specified category. |
| clear_remap_table() | Clears the color-remap table for the default category. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Clears the color-remap table for a specified category. |
| clear_threshold() | Clears the threshold value for the default category. |
| [clear_threshold(type)](#clear_threshold_type_8) | Clears the threshold value for a specified category. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Sets the color-remap table for the brush category. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Sets the color key for the default category. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Sets the color key (transparency range) for a specified category. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Sets the color-adjustment matrix for the default category. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Sets the color-adjustment matrix for the default category. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Sets the color-adjustment matrix for a specified category. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Sets the gamma value for the default category. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Sets the gamma value for a specified category. |
| set_no_op() | Turns off color adjustment for the default category. |
| [set_no_op(type)](#set_no_op_type_20) | Turns off color adjustment for a specified category. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Sets the output channel color-profile file for the default category. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Sets the output channel color-profile file for a specified category. |
| [set_remap_table(map)](#set_remap_table_map_25) | Sets the color-remap table for the default category. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Sets the color-remap table for a specified category. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Sets the threshold (transparency range) for the default category. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Sets the threshold (transparency range) for a specified category. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initializes a new instance of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class.

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Clears the color key (transparency range) for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color key is cleared. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Clears the color-adjustment matrix for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color-adjustment matrix is cleared. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Disables gamma correction for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which gamma correction is disabled. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Clears the NoOp setting for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the NoOp setting is cleared. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Clears the (cyan-magenta-yellow-black) output channel setting for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the output channel setting is cleared. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Clears the output channel color profile setting for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the output channel profile setting is cleared. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Clears the color-remap table for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the remap table is cleared. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Clears the threshold value for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the threshold is cleared. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Sets the color-remap table for the brush category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | An array of [ColorMap](/imaging/python-net/aspose.imaging/colormap/) objects. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Sets the color key for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | The low color-key value. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | The high color-key value. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Sets the color key (transparency range) for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | The low color-key value. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | The high color-key value. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color key is set. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The grayscale-adjustment matrix. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The grayscale-adjustment matrix. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | An element of [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The grayscale-adjustment matrix. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | An element of [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color-adjustment and grayscale-adjustment matrices are set. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Sets the color-adjustment matrix for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Sets the color-adjustment matrix for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | An element of [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment matrix. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Sets the color-adjustment matrix for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | The color-adjustment matrix. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | An element of [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment matrix. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color-adjustment matrix is set. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Sets the gamma value for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | The gamma correction value. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Sets the gamma value for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | The gamma correction value. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of the [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) enumeration that specifies the category for which the gamma value is set. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Turns off color adjustment for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which color correction is turned off. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | An element of [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) that specifies the output channel. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | An element of [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) that specifies the output channel. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the output channel is set. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Sets the output channel color-profile file for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\System32\Spool\Drivers\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Sets the output channel color-profile file for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\System32\Spool\Drivers\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the output channel color-profile file is set. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Sets the color-remap table for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | An array of color pairs of type [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Sets the color-remap table for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | An array of color pairs of type [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color-remap table is set. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Sets the threshold (transparency range) for the default category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | float | A real number that specifies the threshold value. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Sets the threshold (transparency range) for a specified category.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | float | A threshold value from 0.0 to 1.0 that is used as a breakpoint to sort colors that will be mapped to either a maximum or a minimum value. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | An element of [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) that specifies the category for which the color threshold is set. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | An element of [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how repeated copies of an image are used to tile an area. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | An element of [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how repeated copies of an image are used to tile an area. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) and the source rectangle passed to DrawImage is larger than the image itself. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | An element of [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how repeated copies of an image are used to tile an area. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | A color object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) and the source rectangle passed to DrawImage is larger than the image itself. |
| clamp | bool | This parameter has no effect. Set it to false. |

