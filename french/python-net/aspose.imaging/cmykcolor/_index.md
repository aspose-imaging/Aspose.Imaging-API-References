---
title: "Classe CmykColor"
type: docs
weight: 1130
url: /fr/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initialise une nouvelle instance de la classe CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | System.Byte | r | Obtient la valeur du composant cyan de cette structure [Color](/imaging/python-net/aspose.imaging/color/). |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Obtient le vide. |
| is_empty | bool | r | Obtient une valeur indiquant si cette structure [Color](/imaging/python-net/aspose.imaging/color/) est non initialisée. |
| k | System.Byte | r | Obtient la valeur du composant noir de cette structure [Color](/imaging/python-net/aspose.imaging/color/). |
| m | System.Byte | r | Obtient la valeur du composant magenta de cette structure [Color](/imaging/python-net/aspose.imaging/color/). |
| y | System.Byte | r | Obtient la valeur du composant jaune de cette structure [Color](/imaging/python-net/aspose.imaging/color/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crée une structure [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | La conversion de 32-bit ARGB vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | La valeur to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initialise une nouvelle instance de la classe CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crée une structure [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| yellow | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| black | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Le [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de la couleur ARGB 32 bits. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Le [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les pixels du format ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

La conversion de 32-bit ARGB vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixel | int | Le pixel du format ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Le [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser le plus efficace [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int[] | Les pixels du format ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Le tableau des couleurs ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau des couleurs ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Le pixel de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Le [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Le pixel de type CMYKColor au format CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Le [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau des couleurs ARGB. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Les pixels de type CMYKColor au format CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

La valeur to.

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur CMYK longue. |


