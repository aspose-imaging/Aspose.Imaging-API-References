---
title: "PixelDataFormat klass"
type: docs
weight: 6920
url: /sv/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Definierad för 16 bitar per pixel med upp till 16 bitar som representerar gråskaleintensitet. |
| bits_per_pixel | int | r | Hämtar bitarna per pixel. |
| rubrik | string | r | Hämtar rubriken för pixeldataformatet. |
| channel_bits | int[] | r | Hämtar bitantalet för varje kanal. |
| channels_count | int | r | Hämtar antalet kanaler. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 32 bitar per pixel med 8 bitar för varje cyan, magenta, gul och svart. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar acmyk. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och en extra 8-bitars alfakomponent. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | Hämtar pixelformatet. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 16 bitar per pixel med 5 bitar för varje röd, grön och blå, alfa är inte definierad. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå, alfa är inte definierad. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 32 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för indexerad 1 bit per färg.<br/>            Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används.<br/>            Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för indexerad 2 bitar per färg.<br/>            Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används.<br/>            Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för indexerad 4 bitar per färg.<br/>            Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används.<br/>            Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för indexerad 8 bitar per färg.<br/>            Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används.<br/>            Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 32 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 24 bitar per pixel med 8 bitar för varje av luma-, blå-differens- och röd-differens kromakomponent. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) definierad för 32 bitar per pixel med 8 bitar för varje av luma-, blå-differens-, röd-differens- och svart kromakomponent. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Hämtar BGRA-färg med ett specificerat antal bitar per prov. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Hämtar BGRA-färg med ett specificerat antal bitar per prov. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Hämtar CIE Lab-färg med ett specificerat antal bitar per prov. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Hämtar CMYKA-färg med ett specificerat antal bitar per prov. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Hämtar Gråskala-färg med ett specificerat antal bitar per prov. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Hämtar GråskalaAlpha-färg med ett specificerat antal bitar per prov. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Hämtar GråskalaAlpha-färg med ett specificerat antal bitar per prov. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Hämtar BGRA-indexerad färg med ett specificerat antal bitar per prov. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Hämtar RGBA-färg med ett specificerat antal bitar per prov. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Hämtar RGBA-färg med ett specificerat antal bitar per prov. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Hämtar YCbCr-färg med ett specificerat antal bitar per prov. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Hämtar YCbCr-färg med ett specificerat antal bitar per prov. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Hämtar YCCK-färg med ett specificerat antal bitar per prov. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Hämtar BGRA-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA-färgen. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Hämtar BGRA-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA-färgen. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Hämtar CIE Lab-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_l | int | Antalet bitar per L-kanal. |
| bits_per_a | int | Antalet bitar per A-kanal. |
| bits_per_b | int | Antalet bitar per B-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CIE Lab-färgen. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_cyan_channel | int | Antalet bitar per Cyan-kanal. |
| bits_per_magenta_channel | int | Antalet bitar per Magenta-kanal. |
| bits_per_yellow_channel | int | Antalet bitar per Gul-kanal. |
| bits_per_key_channel | int | Antalet bitar per Key-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK-färgen. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK-färgen. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Hämtar CMYKA-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_cyan_channel | int | Antalet bitar per Cyan-kanal. |
| bits_per_magenta_channel | int | Antalet bitar per Magenta-kanal. |
| bits_per_yellow_channel | int | Antalet bitar per Gul-kanal. |
| bits_per_key_channel | int | Antalet bitar per Key-kanal. |
| bits_per_alpha_channel | int | Antalet bitar per Alpha-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | CMYK-färgen. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Hämtar Gråskala-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Gråskala-färgen. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Hämtar GråskalaAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | GråskalaAlpha-färgen. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Hämtar GråskalaAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |
| alpha_channel_bits | int | Antalet bitar per prov i alpha-kanalen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | GråskalaAlpha-färgen. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_red_channel | int | Antalet bitar per Röd-kanal. |
| bits_per_green_channel | int | Antalet bitar per Grön-kanal. |
| bits_per_blue_channel | int | Antalet bitar per Blå-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB-färgen. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGB-färgen. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Hämtar BGRA-indexerad färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | BGRA-färgen. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Hämtar RGBA-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_red_channel | int | Antalet bitar per Röd-kanal. |
| bits_per_green_channel | int | Antalet bitar per Grön-kanal. |
| bits_per_blue_channel | int | Antalet bitar per Blå-kanal. |
| bits_per_alpha_channel | int | Antalet bitar per Alpha-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA-färgen. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Hämtar RGBA-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | RGBA-färgen. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Hämtar YCbCr-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr-färgen. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Hämtar YCbCr-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_y | int | Antalet bitar per Y-kanal. |
| bits_per_cb | int | Antalet bitar per Cb-kanal. |
| bits_per_cr | int | Antalet bitar per Cr-kanal. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCbCr-färgen. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Hämtar YCCK-färg med ett specificerat antal bitar per prov.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bits_per_sample | int | Antalet bitar per prov. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | YCCK-färgen. |


