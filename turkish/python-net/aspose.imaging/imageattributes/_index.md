---
title: "ImageAttributes Sınıfı"
type: docs
weight: 5660
url: /tr/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Yeni bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) sınıfı örneğini başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| clear_brush_remap_table() | Bu [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesinin fırça renk yeniden eşleme tablosunu temizler. |
| clear_color_key() | Varsayılan kategori için renk anahtarını (saydamlık aralığını) temizler. |
| [clear_color_key(type)](#clear_color_key_type_1) | Belirtilen kategori için renk anahtarını (saydamlık aralığını) temizler. |
| clear_color_matrix() | Varsayılan kategori için renk ayarlama matrisini temizler. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Belirtilen kategori için renk ayarlama matrisini temizler. |
| clear_gamma() | Varsayılan kategori için gama düzeltmesini devre dışı bırakır. |
| [clear_gamma(type)](#clear_gamma_type_3) | Belirtilen kategori için gama düzeltmesini devre dışı bırakır. |
| clear_no_op() | Varsayılan kategori için NoOp ayarını temizler. |
| [clear_no_op(type)](#clear_no_op_type_4) | Belirtilen kategori için NoOp ayarını temizler. |
| clear_output_channel() | Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Belirtilen kategori için (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| clear_output_channel_color_profile() | Varsayılan kategori için çıkış kanalı renk profili ayarını temizler. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Belirtilen kategori için çıkış kanalı renk profili ayarını temizler. |
| clear_remap_table() | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Belirtilen kategori için renk yeniden eşleme tablosunu temizler. |
| clear_threshold() | Varsayılan kategori için eşik değerini temizler. |
| [clear_threshold(type)](#clear_threshold_type_8) | Belirtilen kategori için eşik değerini temizler. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Varsayılan kategori için renk anahtarını ayarlar. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Belirtilen kategori için renk anahtarını (şeffaflık aralığını) ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Belirtilen kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Belirtilen kategori için renk ayarlama matrisini ayarlar. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Varsayılan kategori için gama değerini ayarlar. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Belirtilen kategori için gama değerini ayarlar. |
| set_no_op() | Varsayılan kategori için renk ayarlamayı kapatır. |
| [set_no_op(type)](#set_no_op_type_20) | Belirtilen kategori için renk ayarlamayı kapatır. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Belirtilen kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Belirtilen kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [set_remap_table(map)](#set_remap_table_map_25) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Varsayılan kategori için eşik değerini (şeffaflık aralığını) ayarlar. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Belirtilen kategori için eşik değerini (şeffaflık aralığını) ayarlar. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Yeni bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) sınıfı örneğini başlatır.

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Belirtilen kategori için renk anahtarını (saydamlık aralığını) temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk anahtarının temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Belirtilen kategori için renk ayarlama matrisini temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk ayarlama matrisinin temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Belirtilen kategori için gama düzeltmesini devre dışı bırakır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Gama düzeltmesinin devre dışı bırakıldığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Belirtilen kategori için NoOp ayarını temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | NoOp ayarının temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Belirtilen kategori için (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Çıktı kanal ayarının temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Belirtilen kategori için çıkış kanalı renk profili ayarını temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Çıktı kanal profili ayarının temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Belirtilen kategori için renk yeniden eşleme tablosunu temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Yeniden eşleme tablosunun temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Belirtilen kategori için eşik değerini temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Eşik değerinin temizlendiği kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | [ColorMap](/imaging/python-net/aspose.imaging/colormap/) nesnelerinden oluşan bir dizi. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Varsayılan kategori için renk anahtarını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Düşük renk anahtarı değeri. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Yüksek renk anahtarı değeri. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Belirtilen kategori için renk anahtarını (şeffaflık aralığını) ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Düşük renk anahtarı değeri. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Yüksek renk anahtarı değeri. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk anahtarının ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gri tonlamalı ayarlama matrisi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gri tonlamalı ayarlama matrisi. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Renk ayarlama ve gri tonlamalı ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirten bir [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) öğesi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Belirtilen kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Gri tonlamalı ayarlama matrisi. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Renk ayarlama ve gri tonlamalı ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirten bir [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) öğesi. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk ayarlama ve gri tonlamalı ayarlama matrislerinin ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Varsayılan kategori için renk ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Varsayılan kategori için renk ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirten bir [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) öğesi. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Belirtilen kategori için renk ayarlama matrisini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Renk ayarlama matrisi. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirten bir [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) öğesi. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk ayarlama matrisinin ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Varsayılan kategori için gama değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Gama düzeltme değeri. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Belirtilen kategori için gama değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Gama düzeltme değeri. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Gama değerinin ayarlandığı kategoriyi belirten [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) enum öğesi. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Belirtilen kategori için renk ayarlamayı kapatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk düzeltmenin kapatıldığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Çıktı kanalını belirten bir [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) öğesi. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Belirtilen kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Çıktı kanalını belirten bir [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) öğesi. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Çıktı kanalının ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_profile_filename | string | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise, bu parametre dosya adı olabilir. Aksi takdirde, bu parametre tam nitelikli yol adı olmalıdır. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Belirtilen kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_profile_filename | string | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise, bu parametre dosya adı olabilir. Aksi takdirde, bu parametre tam nitelikli yol adı olmalıdır. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Çıktı kanal renk profili dosyasının ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | [ColorMap](/imaging/python-net/aspose.imaging/colormap/) türünde renk çiftlerinden oluşan bir dizi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | [ColorMap](/imaging/python-net/aspose.imaging/colormap/) türünde renk çiftlerinden oluşan bir dizi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Renk yeniden eşleme tablosunun ayarlandığı kategoriyi belirten bir [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Varsayılan kategori için eşik değerini (şeffaflık aralığını) ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| eşik | float | Eşik değerini belirten gerçek bir sayı. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Belirtilen kategori için eşik değerini (şeffaflık aralığını) ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| eşik | float | 0.0 ile 1.0 arasında bir eşik değeri; bu değer, maksimum ya da minimum bir değere eşlenecek renkleri sıralamak için bir kesme noktası olarak kullanılır. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) öğesi, renk eşiğinin ayarlandığı kategoriyi belirtir. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) öğesi, bir görüntünün tekrarlanan kopyalarının bir alanı döşemek için nasıl kullanılacağını belirtir. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) öğesi, bir görüntünün tekrarlanan kopyalarının bir alanı döşemek için nasıl kullanılacağını belirtir. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesi, işlenmiş bir görüntünün dışındaki piksellerin rengini belirtir. Bu renk, mod parametresi [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için döşenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) öğesi, bir görüntünün tekrarlanan kopyalarının bir alanı döşemek için nasıl kullanılacağını belirtir. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Bir renk nesnesi, işlenmiş bir görüntünün dışındaki piksellerin rengini belirtir. Bu renk, mod parametresi [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgen görüntünün kendisinden daha büyük olduğunda görünür. |
| clamp | bool | Bu parametrenin bir etkisi yoktur. Yanlış (false) olarak ayarlayın. |

