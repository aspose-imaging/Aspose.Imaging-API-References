---
title: "ImageAttributes‑klass"
type: docs
weight: 5660
url: /sv/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initierar en ny instans av klassen [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_brush_remap_table() | Rensar penselns färg‑omkartläggningstabell för detta [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objekt. |
| clear_color_key() | Rensar färgnyckeln (transparentintervall) för standardkategorin. |
| [clear_color_key(type)](#clear_color_key_type_1) | Rensar färgnyckeln (transparentintervall) för en angiven kategori. |
| clear_color_matrix() | Rensar färgjusteringsmatrisen för standardkategorin. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Rensar färgjusteringsmatrisen för en angiven kategori. |
| clear_gamma() | Inaktiverar gammakorrigering för standardkategorin. |
| [clear_gamma(type)](#clear_gamma_type_3) | Inaktiverar gammakorrigering för en angiven kategori. |
| clear_no_op() | Rensar NoOp‑inställningen för standardkategorin. |
| [clear_no_op(type)](#clear_no_op_type_4) | Rensar NoOp‑inställningen för en angiven kategori. |
| clear_output_channel() | Rensar CMYK (cyan-magenta-yellow-black) utkanalinställningen för standardkategorin. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Rensar (cyan-magenta-yellow-black) utkanalinställningen för en angiven kategori. |
| clear_output_channel_color_profile() | Rensar utkanalens färgprofilinställning för standardkategorin. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Rensar utkanalens färgprofilinställning för en angiven kategori. |
| clear_remap_table() | Rensar färg‑omkartläggningstabellen för standardkategorin. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Rensar färg‑omkartläggningstabellen för en angiven kategori. |
| clear_threshold() | Rensar tröskelvärdet för standardkategorin. |
| [clear_threshold(type)](#clear_threshold_type_8) | Rensar tröskelvärdet för en angiven kategori. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Ställer in färg‑omkartläggningstabellen för penselkategorin. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Ställer in färgnyckeln för standardkategorin. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Ställer in färgnyckeln (transparentintervall) för en specificerad kategori. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Ställer in färgjusteringsmatrisen för en specificerad kategori. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Ställer in gammavärdet för standardkategorin. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Ställer in gammavärdet för en specificerad kategori. |
| set_no_op() | Stänger av färgjustering för standardkategorin. |
| [set_no_op(type)](#set_no_op_type_20) | Stänger av färgjustering för en specificerad kategori. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Ställer in CMYK (cyan-magenta-gul-svart) utkanal för standardkategorin. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Ställer in CMYK (cyan-magenta-gul-svart) utkanal för en specificerad kategori. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Ställer in färgprofilfilen för utkanalen för standardkategorin. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Ställer in färgprofilfilen för utkanalen för en specificerad kategori. |
| [set_remap_table(map)](#set_remap_table_map_25) | Ställer in färg‑omkartläggningstabellen för standardkategorin. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Ställer in färg‑omkartläggningstabellen för en specificerad kategori. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Ställer in tröskeln (transparentintervall) för standardkategorin. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Ställer in tröskeln (transparentintervall) för en specificerad kategori. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initierar en ny instans av klassen [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/).

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Rensar färgnyckeln (transparentintervall) för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgnyckeln rensas. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Rensar färgjusteringsmatrisen för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgjusteringsmatrisen rensas. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Inaktiverar gammakorrigering för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken gammakorrigering är inaktiverad. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Rensar NoOp‑inställningen för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken NoOp‑inställningen rensas. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Rensar (cyan-magenta-yellow-black) utkanalinställningen för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken utgångskanalsinställningen rensas. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Rensar utkanalens färgprofilinställning för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken profilinställning för utgångskanalen rensas. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Rensar färg‑omkartläggningstabellen för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken ommappningstabellen rensas. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Rensar tröskelvärdet för en angiven kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken tröskelvärdet rensas. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Ställer in färg‑omkartläggningstabellen för penselkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | En array av [ColorMap](/imaging/python-net/aspose.imaging/colormap/)-objekt. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Ställer in färgnyckeln för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Det låga färgnyckelvärdet. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Det höga färgnyckelvärdet. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Ställer in färgnyckeln (transparentintervall) för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Det låga färgnyckelvärdet. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Det höga färgnyckelvärdet. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgnyckeln sätts. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gråskalajusteringsmatrisen. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gråskalajusteringsmatrisen. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ett element av [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) som specificerar typen av bild och färg som kommer att påverkas av färgjusterings- och gråskalajusteringsmatriserna. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gråskalajusteringsmatrisen. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ett element av [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) som specificerar typen av bild och färg som kommer att påverkas av färgjusterings- och gråskalajusteringsmatriserna. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgjusterings- och gråskalajusteringsmatriserna sätts. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ett element av [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Ställer in färgjusteringsmatrisen för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Färgjusteringsmatrisen. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ett element av [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgjusteringsmatrisen sätts. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Ställer in gammavärdet för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gammakorrigeringsvärdet. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Ställer in gammavärdet för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gammakorrigeringsvärdet. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/)‑enumerationen som specificerar kategorin för vilken gamma‑värdet sätts. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Stänger av färgjustering för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgkorrigering är avstängd. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Ställer in CMYK (cyan-magenta-gul-svart) utkanal för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Ett element av [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) som specificerar utgångskanalen. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Ställer in CMYK (cyan-magenta-gul-svart) utkanal för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Ett element av [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) som specificerar utgångskanalen. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken utgångskanalen sätts. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Ställer in färgprofilfilen för utkanalen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_profile_filename | string | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen ligger i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Ställer in färgprofilfilen för utkanalen för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_profile_filename | string | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen ligger i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgprofilfil för utgångskanalen sätts. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Ställer in färg‑omkartläggningstabellen för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | En array av färgpar av typen [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Varje färgpar innehåller en befintlig färg (det första värdet) och den färg som den kommer att mappas till (det andra värdet). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Ställer in färg‑omkartläggningstabellen för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | En array av färgpar av typen [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Varje färgpar innehåller en befintlig färg (det första värdet) och den färg som den kommer att mappas till (det andra värdet). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färg‑ommapningstabellen sätts. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Ställer in tröskeln (transparentintervall) för standardkategorin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | float | Ett reellt tal som specificerar tröskelvärdet. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Ställer in tröskeln (transparentintervall) för en specificerad kategori.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | float | Ett tröskelvärde från 0,0 till 1,0 som används som en brytpunkt för att sortera färger som kommer att mappas till antingen ett maximalt eller ett minimalt värde. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ett element av [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) som specificerar kategorin för vilken färgtröskeln är inställd. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ett element av [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ett element av [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Ett [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)‑objekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) och källrektangeln som skickas till DrawImage är större än själva bilden. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. En textur tileas över en form för att fylla i den när texturen är mindre än formen den fyller.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ett element av [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Ett färgobjekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är inställd på [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) och källrektangeln som skickas till DrawImage är större än själva bilden. |
| klämma | bool | Denna parameter har ingen effekt. Sätt den till false. |

