---
title: "PixelDataFormat Klasse"
type: docs
weight: 6920
url: /de/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Definiert für 16 Bit pro Pixel mit bis zu 16 Bit, die die Graustufenintensität darstellen. |
| bits_per_pixel | int | r | Liefert die Bits pro Pixel. |
| Beschriftung | string | r | Liefert die Beschriftung des Pixel-Datenformates. |
| channel_bits | int[] | r | Liefert die Bitanzahl für jeden Kanal. |
| channels_count | int | r | Liefert die Kanalanzahl. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 32 Bit pro Pixel mit 8 Bit für jedes der Cyan, Magenta, Gelb und Schwarz. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das acmyk. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 8 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0-255 darstellen. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 16 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0-255 darstellen, und einem zusätzlichen 8-Bit-Alpha-Komponente. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | Liefert das Pixel-Format. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 16 Bit pro Pixel mit 5 Bit für jedes der Rot, Grün und Blau, Alpha ist nicht definiert. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 16 Bit pro Pixel mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau, Alpha ist nicht definiert. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 24 Bit pro Pixel mit 8 Bit für jeweils Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 24 Bit pro Pixel mit 8 Bit für jeweils Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 32 Bit pro Pixel mit 8 Bit für jeweils Alpha, Rot, Grün und Blau. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für indiziertes 1 Bit pro Farbe.<br/>            Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird.<br/>            Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich sein kann. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für indiziertes 2 Bit pro Farbe.<br/>            Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird.<br/>            Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich sein kann. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für indiziertes 4 Bit pro Farbe.<br/>            Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird.<br/>            Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich sein kann. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für indiziertes 8 Bit pro Farbe.<br/>            Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird.<br/>            Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich sein kann. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 32 Bit pro Pixel mit 8 Bit für jeweils Alpha, Rot, Grün und Blau. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 24 Bit pro Pixel mit 8 Bit für jeweils die Luma-, Blau-Differenz- und Rot-Differenz-Chromakomponenten. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liefert das [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definiert für 32 Bit pro Pixel mit 8 Bit für jeweils die Luma-, Blau-Differenz-, Rot-Differenz- und Schwarz-Chromakomponenten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Liefert BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Liefert BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Liefert CIE Lab-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Liefert CMYK-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Liefert CMYK-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Liefert CMYKA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Liefert Graustufenfarbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Liefert GraustufenAlpha-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Liefert GraustufenAlpha-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Liefert RGB-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Liefert RGB-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Liefert indizierte BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Liefert RGBA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Liefert RGBA-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Liefert YCbCr-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Liefert YCbCr-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Liefert YCCK-Farbe mit einer angegebenen Anzahl von Bits pro Sample. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Liefert BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die BGRA-Farbe. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Liefert BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die BGRA-Farbe. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Liefert CIE Lab-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_l | int | Die Anzahl der Bits pro L-Kanal. |
| bits_per_a | int | Die Anzahl der Bits pro A-Kanal. |
| bits_per_b | int | Die Anzahl der Bits pro B-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die CIE Lab-Farbe. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Liefert CMYK-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_cyan_channel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bits_per_magenta_channel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bits_per_yellow_channel | int | Die Anzahl der Bits pro Gelb-Kanal. |
| bits_per_key_channel | int | Die Anzahl der Bits pro Key-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die CMYK-Farbe. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Liefert CMYK-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die CMYK-Farbe. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Liefert CMYKA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_cyan_channel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bits_per_magenta_channel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bits_per_yellow_channel | int | Die Anzahl der Bits pro Gelb-Kanal. |
| bits_per_key_channel | int | Die Anzahl der Bits pro Key-Kanal. |
| bits_per_alpha_channel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die CMYK-Farbe. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Liefert Graustufenfarbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die Graustufenfarbe. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Liefert GraustufenAlpha-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die GraustufenAlpha-Farbe. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Liefert GraustufenAlpha-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |
| alpha_channel_bits | int | Die Anzahl der Bits pro Probe im Alpha-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die GraustufenAlpha-Farbe. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Liefert RGB-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_red_channel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bits_per_green_channel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bits_per_blue_channel | int | Die Anzahl der Bits pro Blau-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die RGB-Farbe. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Liefert RGB-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die RGB-Farbe. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Liefert indizierte BGRA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die BGRA-Farbe. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Liefert RGBA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_red_channel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bits_per_green_channel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bits_per_blue_channel | int | Die Anzahl der Bits pro Blau-Kanal. |
| bits_per_alpha_channel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die RGBA-Farbe. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Liefert RGBA-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die RGBA-Farbe. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Liefert YCbCr-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die YCbCr-Farbe. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Liefert YCbCr-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_y | int | Die Anzahl der Bits pro Y-Kanal. |
| bits_per_cb | int | Die Anzahl der Bits pro Cb-Kanal. |
| bits_per_cr | int | Die Anzahl der Bits pro Cr-Kanal. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die YCbCr-Farbe. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Liefert YCCK-Farbe mit einer angegebenen Anzahl von Bits pro Sample.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bits_per_sample | int | Die Anzahl der Bits pro Sample. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Die YCCK-Farbe. |


