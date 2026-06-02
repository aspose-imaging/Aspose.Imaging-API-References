---
title: "CmykColor Sınıfı"
type: docs
weight: 1130
url: /tr/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | CmykColor sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| c | System.Byte | r | Bu [Color](/imaging/python-net/aspose.imaging/color/) yapısının camgöbeği (cyan) bileşen değerini alır. |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Boş olanı alır. |
| is_empty | bool | r | Bu [Color](/imaging/python-net/aspose.imaging/color/) yapısının başlatılmamış olup olmadığını gösteren bir değer alır. |
| k | System.Byte | r | Bu [Color](/imaging/python-net/aspose.imaging/color/) yapısının siyah (black) bileşen değerini alır. |
| m | System.Byte | r | Bu [Color](/imaging/python-net/aspose.imaging/color/) yapısının macenta (magenta) bileşen değerini alır. |
| y | System.Byte | r | Bu [Color](/imaging/python-net/aspose.imaging/color/) yapısının sarı (yellow) bileşen değerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 32 bit camgöbeği, macenta, sarı ve siyah değerlerinden bir [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) yapısı oluşturur.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | CMYKColor'dan 32 bit ARGB Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın. |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | 32-bit ARGB'den CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | 32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın. |
| [to_value()](#to_value__18) | Bu to değeri. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

CmykColor sınıfının yeni bir örneğini başlatır

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

32 bit camgöbeği, macenta, sarı ve siyah değerlerinden bir [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) yapısı oluşturur.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın.

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
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Bu [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

CMYKColor'dan 32 bit ARGB Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | 32-bit ARGB renginin dizisi. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Bu [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | 32-bit ARGB formatındaki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Bu [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

32-bit ARGB'den CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixel | int | 32-bit ARGB formatındaki piksel. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Bu [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

32 bit ARGB renginden CMYKColor'a dönüşüm.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int[] | 32-bit ARGB formatındaki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Bu [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ARGB renklerinin dizisi. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renklerinin dizisi. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki piksel. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki piksel. |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Bu [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ARGB renklerinin dizisi. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

CMYKColor'dan Color'a icc dönüşümü ile varsayılan profiller kullanılarak dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

CMYKColor'dan Color'a icc dönüşümü ile dönüşüm.<br/>            Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK formatındaki CMYKColor tipindeki pikseller. |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Bu [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

Bu to değeri.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Uzun CMYK değeri. |


