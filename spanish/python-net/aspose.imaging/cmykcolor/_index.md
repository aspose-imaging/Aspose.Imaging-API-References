---
title: "Clase CmykColor"
type: docs
weight: 1130
url: /es/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Inicializa una nueva instancia de la clase CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| c | System.Byte | r | Obtiene el valor del componente cian de esta estructura [Color](/imaging/python-net/aspose.imaging/color/). |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Obtiene el vacío. |
| is_empty | bool | r | Obtiene un valor que indica si esta estructura [Color](/imaging/python-net/aspose.imaging/color/) no está inicializada. |
| k | System.Byte | r | Obtiene el valor del componente negro de esta estructura [Color](/imaging/python-net/aspose.imaging/color/). |
| m | System.Byte | r | Obtiene el valor del componente magenta de esta estructura [Color](/imaging/python-net/aspose.imaging/color/). |
| y | System.Byte | r | Obtiene el valor del componente amarillo de esta estructura [Color](/imaging/python-net/aspose.imaging/color/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crea una estructura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) a partir de valores de cian, magenta, amarillo y negro de 32 bits.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | La conversión de 32-bit ARGB a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | El valor to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Inicializa una nueva instancia de la clase CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crea una estructura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) a partir de valores de cian, magenta, amarillo y negro de 32 bits.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | El arreglo del color ARGB de 32 bits. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los píxeles del formato ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | El [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

La conversión de 32-bit ARGB a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixel | int | El píxel del formato ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use el más efectivo [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int[] | Los píxeles del formato ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | El [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El arreglo de los colores ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El arreglo de los colores ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El píxel de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | El píxel de tipo CMYKColor en formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El arreglo de los colores ARGB. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una alternativa más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Los píxeles de tipo CMYKColor en formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | El [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

El valor to.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor largo CMYK. |


