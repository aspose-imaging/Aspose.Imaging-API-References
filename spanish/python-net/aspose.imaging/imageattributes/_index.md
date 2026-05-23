---
title: "Clase ImageAttributes"
type: docs
weight: 5660
url: /es/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Inicializa una nueva instancia de la clase [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| clear_brush_remap_table() | Borra la tabla de remapeo de colores del pincel de este objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| clear_color_key() | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [clear_color_key(type)](#clear_color_key_type_1) | Borra la clave de color (rango de transparencia) para una categoría especificada. |
| clear_color_matrix() | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Borra la matriz de ajuste de color para una categoría especificada. |
| clear_gamma() | Desactiva la corrección gamma para la categoría predeterminada. |
| [clear_gamma(type)](#clear_gamma_type_3) | Desactiva la corrección gamma para una categoría especificada. |
| clear_no_op() | Borra la configuración NoOp para la categoría predeterminada. |
| [clear_no_op(type)](#clear_no_op_type_4) | Borra la configuración NoOp para una categoría especificada. |
| clear_output_channel() | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada. |
| clear_output_channel_color_profile() | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Borra la configuración del perfil de color del canal de salida para una categoría especificada. |
| clear_remap_table() | Borra la tabla de remapeo de colores para la categoría predeterminada. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Borra la tabla de remapeo de colores para una categoría especificada. |
| clear_threshold() | Borra el valor de umbral para la categoría predeterminada. |
| [clear_threshold(type)](#clear_threshold_type_8) | Borra el valor de umbral para una categoría especificada. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Establece la tabla de remapeo de colores para la categoría de pincel. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Establece la clave de color para la categoría predeterminada. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Establece la clave de color (rango de transparencia) para una categoría especificada. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Establece la matriz de ajuste de color para una categoría especificada. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Establece el valor gamma para la categoría predeterminada. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Establece el valor gamma para una categoría especificada. |
| set_no_op() | Desactiva el ajuste de color para la categoría predeterminada. |
| [set_no_op(type)](#set_no_op_type_20) | Desactiva el ajuste de color para una categoría especificada. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Establece el archivo de perfil de color del canal de salida para una categoría especificada. |
| [set_remap_table(map)](#set_remap_table_map_25) | Establece la tabla de remapeo de colores para la categoría predeterminada. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Establece la tabla de remapeo de colores para una categoría especificada. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Establece el umbral (rango de transparencia) para una categoría especificada. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Establece el modo de envoltura que se usa para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Establece el modo de envoltura y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Establece el modo de envoltura y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Inicializa una nueva instancia de la clase [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/).

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Borra la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se borra la clave de color. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Borra la matriz de ajuste de color para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se borra la matriz de ajuste de color. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Desactiva la corrección gamma para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se desactiva la corrección gamma. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Borra la configuración NoOp para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se elimina la configuración NoOp. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se elimina la configuración del canal de salida. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Borra la configuración del perfil de color del canal de salida para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se elimina la configuración del perfil del canal de salida. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Borra la tabla de remapeo de colores para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se elimina la tabla de remapeo. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Borra el valor de umbral para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se elimina el umbral. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Establece la tabla de remapeo de colores para la categoría de pincel.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Una matriz de objetos [ColorMap](/imaging/python-net/aspose.imaging/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Establece la clave de color para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | El valor bajo de la clave de color. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | El valor alto de la clave de color. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Establece la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | El valor bajo de la clave de color. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | El valor alto de la clave de color. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece la clave de color. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de escala de grises. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de escala de grises. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un elemento de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de ajuste de escala de grises. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de escala de grises. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un elemento de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de ajuste de escala de grises. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establecen las matrices de ajuste de color y de ajuste de escala de grises. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un elemento de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Establece la matriz de ajuste de color para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matriz de ajuste de color. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un elemento de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece la matriz de ajuste de color. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Establece el valor gamma para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma | float | El valor de corrección gamma. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Establece el valor gamma para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma | float | El valor de corrección gamma. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de la enumeración [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece el valor gamma. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Desactiva el ajuste de color para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual la corrección de color está desactivada. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Un elemento de [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) que especifica el canal de salida. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Un elemento de [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) que especifica el canal de salida. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece el canal de salida. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Establece el archivo de perfil de color del canal de salida para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_profile_filename | string | La ruta de un archivo de perfil de color. Si el archivo de perfil de color se encuentra en el directorio %SystemRoot%\System32\Spool\Drivers\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Establece el archivo de perfil de color del canal de salida para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_profile_filename | string | La ruta de un archivo de perfil de color. Si el archivo de perfil de color se encuentra en el directorio %SystemRoot%\System32\Spool\Drivers\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece el archivo de perfil de color del canal de salida. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Establece la tabla de remapeo de colores para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Una matriz de pares de colores del tipo [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Establece la tabla de remapeo de colores para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Una matriz de pares de colores del tipo [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece la tabla de remapeo de color. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Establece el umbral (rango de transparencia) para la categoría predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| umbral | float | Un número real que especifica el valor umbral. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Establece el umbral (rango de transparencia) para una categoría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| umbral | float | Un valor umbral de 0.0 a 1.0 que se utiliza como punto de ruptura para ordenar colores que se asignarán a un valor máximo o mínimo. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un elemento de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) que especifica la categoría para la cual se establece el umbral de color. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Establece el modo de envoltura que se usa para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un elemento de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Establece el modo de envoltura y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un elemento de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Un objeto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode se establece en [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Establece el modo de envoltura y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un elemento de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode se establece en [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |
| clamp | bool | Este parámetro no tiene efecto. Establézcalo en false. |

