---
title: "CmykColor-klass"
type: docs
weight: 1130
url: /sv/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initierar en ny instans av CmykColor-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | System.Byte | r | Hämtar cyan‑komponentens värde för denna [Color](/imaging/python-net/aspose.imaging/color/) struktur. |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | Hämtar den tomma. |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna [Color](/imaging/python-net/aspose.imaging/color/) är oinitierad. |
| k | System.Byte | r | Hämtar svart‑komponentens värde för denna [Color](/imaging/python-net/aspose.imaging/color/) struktur. |
| m | System.Byte | r | Hämtar magenta‑komponentens värde för denna [Color](/imaging/python-net/aspose.imaging/color/) struktur. |
| y | System.Byte | r | Hämtar gul‑komponentens värde för denna [Color](/imaging/python-net/aspose.imaging/color/) struktur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Skapar en [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struktur från 32‑bitars cyan-, magenta-, gul- och svart‑värden.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Konverteringen från CMYKColor till 32‑bitars ARGB‑färg med icc‑konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | Konverteringen från 32-bitars ARGB till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/). |
| [to_value()](#to_value__18) | Tillvärdet. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initierar en ny instans av CmykColor-klassen

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Skapar en [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struktur från 32‑bitars cyan-, magenta-, gul- och svart‑värden.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cyan | int | Cyan-komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Magenta-komponenten. Giltiga värden är 0 till 255. |
| yellow | int | Gul-komponenten. Giltiga värden är 0 till 255. |
| black | int | Svart-komponenten. Giltiga värden är 0 till 255. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Den [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Konverteringen från CMYKColor till 32‑bitars ARGB‑färg med icc‑konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Arrayen av 32-bitars ARGB-färg. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Den [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | Pixlar i 32-bitars ARGB-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Den [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

Konverteringen från 32-bitars ARGB till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixel | int | Pixel i 32-bitars ARGB-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Den [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

Konverteringen från 32‑bitars ARGB‑färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int[] | Pixlar i 32-bitars ARGB-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Den [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Arrayen av ARGB-färger. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Arrayen av ARGB-färger. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixel av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Den [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixel av typen CMYKColor i CMYK-format. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Den [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Arrayen av ARGB-färger. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering med standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Pixlar av typen CMYKColor i CMYK-format. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Den [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

Tillvärdet.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det långa CMYK-värdet. |


