---
title: "CmykColorHelper Klasse"
type: docs
weight: 1140
url: /de/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [get_c(cmyk)](#get_c_cmyk_10) | Liefert den Cyan-Komponentenwert. |
| [get_k(cmyk)](#get_k_cmyk_11) | Liefert den Schwarz-Komponentenwert. |
| [get_m(cmyk)](#get_m_cmyk_12) | Liefert den Magenta-Komponentenwert. |
| [get_y(cmyk)](#get_y_cmyk_13) | Liefert den Gelb-Komponentenwert. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit benutzerdefiniertem Profil. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | Konvertiert ARGB zu CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | Konvertiert ARGB zu CMYKA (mit Transparenz). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | Konvertiert RGB zu CMYKA (mit Alpha) unter Verwendung benutzerdefinierter ICC-Profile. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | int | Die ARGB-Farbe. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten.

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
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

Liefert den Cyan-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Cyan-Komponentenwert. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

Liefert den Schwarz-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Schwarz-Komponentenwert. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

Liefert den Magenta-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Magenta-Komponentenwert. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

Liefert den Gelb-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Wert der gelben Komponente. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die ARGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farbe. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit benutzerdefiniertem Profil.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farbe. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Pixel, dargestellt als 32-Bit-Ganzzahlen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Pixel, dargestellt als 32-Bit-Ganzzahlen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die ARGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die ARGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Konvertiert ARGB zu CMYK.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |
| start_index | int | Der Startindex der RGB-Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB-Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die CMYK-Farben, dargestellt als Byte-Array. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |
| start_index | int | Der Startindex der RGB-Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB-Pixel. |
| rgb_icc_stream | _io.BufferedRandom | Der RGB-Profil-Stream. |
| cmyk_icc_stream | _io.BufferedRandom | Der CMYK-Profil-Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die CMYK-Farben, dargestellt als Byte-Array. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | Die ARGB-Farbe. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

Konvertiert ARGB zu CMYKA (mit Transparenz).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int[] | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |
| start_index | int | Der Startindex der RGB-Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB-Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die CMYK-Farben, dargestellt als Byte-Array. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konvertiert RGB zu CMYKA (mit Alpha) unter Verwendung benutzerdefinierter ICC-Profile.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlen. |
| start_index | int | Der Startindex der RGB-Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB-Pixel. |
| rgb_icc_stream | _io.BufferedRandom | Der RGB-Profil-Stream. |
| cmyk_icc_stream | _io.BufferedRandom | Der CMYK-Profil-Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die CMYK-Farben, dargestellt als Byte-Array. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | int | Die ARGB-Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe, dargestellt als 32‑Bit‑Ganzzahlwert in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.<br/>            Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pixel | int[] | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB Icc Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Die CMYK-Farben, dargestellt als 32‑Bit‑Ganzzahlwerte in KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Erhalte eine ganzzahlige Darstellung von Schwarz im CMYK-Farbraum.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Das schwarze Quadrat.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Zeichne das schwarze Quadrat in der Bildmitte.
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

# Die Ausgabe sieht folgendermaßen aus:
# Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

