---
title: "CmykColor Klasse"
type: docs
weight: 1130
url: /de/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initialisiert eine neue Instanz der CmykColor Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| c | System.Byte | r | Liest den Cyan-Komponentenwert dieser [Color](/imaging/python-net/aspose.imaging/color/) Struktur. |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Liest das Leere. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Color](/imaging/python-net/aspose.imaging/color/) Struktur nicht initialisiert ist. |
| k | System.Byte | r | Liest den Schwarz-Komponentenwert dieser [Color](/imaging/python-net/aspose.imaging/color/) Struktur. |
| m | System.Byte | r | Liest den Magenta-Komponentenwert dieser [Color](/imaging/python-net/aspose.imaging/color/) Struktur. |
| y | System.Byte | r | Liest den Gelb-Komponentenwert dieser [Color](/imaging/python-net/aspose.imaging/color/) Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Erstellt eine [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) Struktur aus 32‑Bit Cyan-, Magenta-, Gelb- und Schwarzwerten.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Die Konvertierung von CMYKColor zu 32‑Bit ARGB Color mittels ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | Die Konvertierung von 32‑Bit ARGB zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | Der to-Wert. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initialisiert eine neue Instanz der CmykColor Klasse

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Erstellt eine [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) Struktur aus 32‑Bit Cyan-, Magenta-, Gelb- und Schwarzwerten.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cyan | int | Die Cyan-Komponente. Gültige Werte sind 0 bis 255. |
| magenta | int | Die Magenta-Komponente. Gültige Werte sind 0 bis 255. |
| yellow | int | Die Gelb-Komponente. Gültige Werte sind 0 bis 255. |
| black | int | Die Schwarz-Komponente. Gültige Werte sind 0 bis 255. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Das [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu 32‑Bit ARGB Color mittels ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Array der 32‑Bit ARGB‑Farbe. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Das [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die Pixel des 32‑Bit ARGB‑Formats. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

Die Konvertierung von 32‑Bit ARGB zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixel | int | Der Pixel des 32‑Bit ARGB‑Formats. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Das [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die Pixel des 32‑Bit ARGB‑Formats. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Das Array der ARGB‑Farben. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Array der ARGB‑Farben. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑CMYK‑Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑RGB‑Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑CMYK‑Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑RGB‑Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Der Pixel des Typs CMYKColor im CMYK‑Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Das [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Der Pixel des Typs CMYKColor im CMYK‑Format. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑CMYK‑Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑RGB‑Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Das [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Array der ARGB‑Farben. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color unter Verwendung der ICC‑Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Die Pixel des Typs CMYKColor im CMYK-Format. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑CMYK‑Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das ICC‑RGB‑Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

Der to-Wert.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der lange CMYK‑Wert. |


