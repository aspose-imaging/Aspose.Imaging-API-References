---
title: "ImageAttributes 类"
type: docs
weight: 5660
url: /zh/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | 初始化 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 类的新实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| clear_brush_remap_table() | 清除此 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象的画笔颜色映射表。 |
| clear_color_key() | 清除默认类别的颜色键（透明度范围）。 |
| [clear_color_key(type)](#clear_color_key_type_1) | 清除指定类别的颜色键（透明度范围）。 |
| clear_color_matrix() | 清除默认类别的颜色调整矩阵。 |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | 清除指定类别的颜色调整矩阵。 |
| clear_gamma() | 禁用默认类别的伽马校正。 |
| [clear_gamma(type)](#clear_gamma_type_3) | 禁用指定类别的伽马校正。 |
| clear_no_op() | 清除默认类别的 NoOp 设置。 |
| [clear_no_op(type)](#clear_no_op_type_4) | 清除指定类别的 NoOp 设置。 |
| clear_output_channel() | 清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。 |
| [clear_output_channel(type)](#clear_output_channel_type_5) | 清除指定类别的（青-品红-黄-黑）输出通道设置。 |
| clear_output_channel_color_profile() | 清除默认类别的输出通道颜色配置文件设置。 |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | 清除指定类别的输出通道颜色配置文件设置。 |
| clear_remap_table() | 清除默认类别的颜色映射表。 |
| [clear_remap_table(type)](#clear_remap_table_type_7) | 清除指定类别的颜色映射表。 |
| clear_threshold() | 清除默认类别的阈值。 |
| [clear_threshold(type)](#clear_threshold_type_8) | 清除指定类别的阈值。 |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | 为画笔类别设置颜色重新映射表。 |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | 为默认类别设置颜色键。 |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | 为指定类别设置颜色键（透明度范围）。 |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | 为指定类别设置颜色调整矩阵和灰度调整矩阵。 |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | 为默认类别设置颜色调整矩阵。 |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | 为默认类别设置颜色调整矩阵。 |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | 为指定类别设置颜色调整矩阵。 |
| [set_gamma(gamma)](#set_gamma_gamma_18) | 为默认类别设置伽马值。 |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | 为指定类别设置伽马值。 |
| set_no_op() | 关闭默认类别的颜色调整。 |
| [set_no_op(type)](#set_no_op_type_20) | 关闭指定类别的颜色调整。 |
| [set_output_channel(flags)](#set_output_channel_flags_21) | 为默认类别设置 CMYK（青色-品红-黄色-黑色）输出通道。 |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | 为指定类别设置 CMYK（青色-品红-黄色-黑色）输出通道。 |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | 为默认类别设置输出通道颜色配置文件。 |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | 为指定类别设置输出通道颜色配置文件。 |
| [set_remap_table(map)](#set_remap_table_map_25) | 为默认类别设置颜色重新映射表。 |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | 为指定类别设置颜色重新映射表。 |
| [set_threshold(threshold)](#set_threshold_threshold_27) | 为默认类别设置阈值（透明度范围）。 |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | 为指定类别设置阈值（透明度范围）。 |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | 设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | 设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | 设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

初始化 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 类的新实例。

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

清除指定类别的颜色键（透明度范围）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定要清除颜色键的类别。 |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

清除指定类别的颜色调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定要清除颜色调整矩阵的类别。 |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

禁用指定类别的伽马校正。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定要禁用伽马校正的类别。 |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

清除指定类别的 NoOp 设置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定清除 NoOp 设置的类别。 |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

清除指定类别的（青-品红-黄-黑）输出通道设置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定清除输出通道设置的类别。 |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

清除指定类别的输出通道颜色配置文件设置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定清除输出通道配置文件设置的类别。 |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

清除指定类别的颜色映射表。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定清除重新映射表的类别。 |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

清除指定类别的阈值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定清除阈值的类别。 |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

为画笔类别设置颜色重新映射表。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | 一个由 [ColorMap](/imaging/python-net/aspose.imaging/colormap/) 对象组成的数组。 |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

为默认类别设置颜色键。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | 低颜色键值。 |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | 高颜色键值。 |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

为指定类别设置颜色键（透明度范围）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | 低颜色键值。 |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | 高颜色键值。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置颜色键的类别。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 灰度调整矩阵。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 灰度调整矩阵。 |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | 一个 [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) 元素，指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

为指定类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 灰度调整矩阵。 |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | 一个 [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) 元素，指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置颜色调整和灰度调整矩阵的类别。 |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

为默认类别设置颜色调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

为默认类别设置颜色调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | 一个 [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) 元素，指定将受到颜色调整矩阵影响的图像和颜色类型。 |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

为指定类别设置颜色调整矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 颜色调整矩阵。 |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | 一个 [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) 元素，指定将受到颜色调整矩阵影响的图像和颜色类型。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置颜色调整矩阵的类别。 |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

为默认类别设置伽马值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 伽马校正值。 |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

为指定类别设置伽马值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 伽马校正值。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 枚举元素，指定设置伽马值的类别。 |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

关闭指定类别的颜色调整。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定关闭颜色校正的类别。 |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

为默认类别设置 CMYK（青色-品红-黄色-黑色）输出通道。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | 一个 [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) 元素，指定输出通道。 |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

为指定类别设置 CMYK（青色-品红-黄色-黑色）输出通道。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | 一个 [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) 元素，指定输出通道。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置输出通道的类别。 |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

为默认类别设置输出通道颜色配置文件。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，此参数可以是文件名。否则，此参数必须是完整的路径名。 |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

为指定类别设置输出通道颜色配置文件。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，此参数可以是文件名。否则，此参数必须是完整的路径名。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置输出通道颜色配置文件的类别。 |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

为默认类别设置颜色重新映射表。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | 一个由类型为 [ColorMap](/imaging/python-net/aspose.imaging/colormap/) 的颜色对组成的数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

为指定类别设置颜色重新映射表。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | 一个由类型为 [ColorMap](/imaging/python-net/aspose.imaging/colormap/) 的颜色对组成的数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置颜色重新映射表的类别。 |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

为默认类别设置阈值（透明度范围）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | float | 指定阈值的实数。 |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

为指定类别设置阈值（透明度范围）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | float | 从 0.0 到 1.0 的阈值，用作分割点，以对颜色进行排序，这些颜色将映射到最大值或最小值。 |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 一个 [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) 元素，指定设置颜色阈值的类别。 |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 一个 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 元素，指定如何使用图像的重复副本来平铺区域。 |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 一个 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 元素，指定如何使用图像的重复副本来平铺区域。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) 且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 一个 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 元素，指定如何使用图像的重复副本来平铺区域。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个颜色对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) 且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |
| 夹紧 | bool | 此参数无效。请将其设为 false。 |

