---
title: "CmykColorHelper Sınıfı"
type: docs
weight: 1140
url: /tr/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | 32-bit camgöbeği, macenta, sarı ve siyah değerlerinden CMYK oluşturur. |
| [get_c(cmyk)](#get_c_cmyk_10) | Camgöbeği bileşen değerini alır. |
| [get_k(cmyk)](#get_k_cmyk_11) | Siyah bileşen değerini alır. |
| [get_m(cmyk)](#get_m_cmyk_12) | Macenta bileşen değerini alır. |
| [get_y(cmyk)](#get_y_cmyk_13) | Sarı bileşen değerini alır. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | Varsayılan profillerle Icc dönüşümü kullanarak CMYK renginden ARGB Rengine dönüşüm. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | Özel profil ile Icc dönüşümü kullanarak CMYK renginden ARGB rengine dönüşüm. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | ARGB'yi CMYK'ye dönüştürür. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | ARGB renginden CMYK rengine dönüşüm. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | ARGB'yi CMYKA'ya (şeffaflık ile) dönüştürür. |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Özel ICC profilleri kullanarak RGB'yi CMYKA'ya (alfa ile) dönüştürür. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değeri olarak sunulur. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | int | ARGB rengi. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

32-bit camgöbeği, macenta, sarı ve siyah değerlerinden CMYK oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cyan | int | Cyan bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| magenta | int | Magenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| yellow | int | Yellow bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| black | int | Black bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Camgöbeği bileşen değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Cyan bileşen değeri. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Siyah bileşen değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Black bileşen değeri. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Macenta bileşen değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Magenta bileşen değeri. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Sarı bileşen değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Sarı bileşen değeri. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

Varsayılan profillerle Icc dönüşümü kullanarak CMYK renginden ARGB Rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB rengi. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profil ile Icc dönüşümü kullanarak CMYK renginden ARGB rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB rengi. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK pikselleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK pikselleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

ARGB'yi CMYK'ye dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| start_index | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | CMYK renkleri bayt dizisi olarak sunulur. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| start_index | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| rgb_icc_stream | _io.BufferedRandom | RGB profil akışı. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK profil akışı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | CMYK renkleri bayt dizisi olarak sunulur. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | ARGB rengi. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

ARGB'yi CMYKA'ya (şeffaflık ile) dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| start_index | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | CMYK renkleri bayt dizisi olarak sunulur. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Özel ICC profilleri kullanarak RGB'yi CMYKA'ya (alfa ile) dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| start_index | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| rgb_icc_stream | _io.BufferedRandom | RGB profil akışı. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK profil akışı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | CMYK renkleri bayt dizisi olarak sunulur. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb | int | ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değeri olarak sunulur. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.<br/>            PSD CMYK formatı KCMY bayt sırasını ters kanal değerleriyle kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| piksel | int[] | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | CMYK renkleri, ters kanal değerleriyle KCMY bayt sırasında 32-bit tam sayı değerleri olarak sunulur.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# CMYK renk uzayında siyahın tam sayı temsili alın.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Siyah kare.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Siyah kareyi görüntünün ortasına çizin.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles. {#example_178}
``` python

from aspose.imaging import Color, CmykColorHelper

rgbColors = [Color.red, Color.green, Color.blue]

print("Convert RGB to CMYK without using ICC profiles.")
for rgbColor in rgbColors:
	cmyk = CmykColorHelper.to_cmyk(rgbColor)
	c = CmykColorHelper.get_c(cmyk)
	m = CmykColorHelper.get_m(cmyk)
	y = CmykColorHelper.get_y(cmyk)
	k = CmykColorHelper.get_k(cmyk)
	print(f"RGB({rgbColor.r},{rgbColor.g},{rgbColor.b})\t\t=> CMYK({c},{m},{y},{k})")

# Çıktı şu şekilde görünür:
# ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

