---
title: PixelDataFormat Class
type: docs
weight: 6710
url: /python-net/aspose.imaging/pixeldataformat/
---

The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

**Aspose.Imaging Version:** 23.6

The PixelDataFormat type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the acmyk. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for indexed 8 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for indexed 4 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for indexed 2 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for indexed 1 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat) | r | Gets the pixel format. |
| bits_per_pixel | int | r | Gets the bits per pixel. |
| channels_count | int | r | Gets the channels count. |
| channel_bits | int | r | Gets the bits count for each channel. |
| caption | string | r | Gets the pixel data format caption. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r/w | Gets the [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Defined for 16 bits per pixel with up to 16 bits representing grayscale intensity. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_0) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_1) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_2) | Gets RGB color with a specified number of bits per sample. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_3) | Gets RGB color with a specified number of bits per sample. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_4) | Gets RGBA color with a specified number of bits per sample. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_5) | Gets RGBA color with a specified number of bits per sample. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_6) | Gets YCbCr color with a specified number of bits per sample. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_7) | Gets YCbCr color with a specified number of bits per sample. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_8) | Gets CMYK color with a specified number of bits per sample. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_9) | Gets CMYK color with a specified number of bits per sample. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_10) | Gets Grayscale color with a specified number of bits per sample. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_11) | Gets BGRA indexed color with a specified number of bits per sample. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_12) | Gets BGRA color with a specified number of bits per sample. |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_13) | Gets BGRA color with a specified number of bits per sample. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_14) | Gets CMYKA color with a specified number of bits per sample. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_15) | Gets YCCK color with a specified number of bits per sample. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_16) | Gets CIE Lab color with a specified number of bits per sample. |

### get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_0}


```
 get_grayscale_alpha(bits_per_sample) 
```

Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The GrayscaleAlpha color. |


### get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_1}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |
| alpha_channel_bits | int | The number of bits per sample in the alpha channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The GrayscaleAlpha color. |


### get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_2}


```
 get_rgb(bits_per_sample) 
```

Gets RGB color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The RGB color. |


### get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_3}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Gets RGB color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | The number of bits per Red channel. |
| bits_per_green_channel | int | The number of bits per Green channel. |
| bits_per_blue_channel | int | The number of bits per Blue channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The RGB color. |


### get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_4}


```
 get_rgba(bits_per_sample) 
```

Gets RGBA color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The RGBA color. |


### get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_5}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Gets RGBA color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | The number of bits per Red channel. |
| bits_per_green_channel | int | The number of bits per Green channel. |
| bits_per_blue_channel | int | The number of bits per Blue channel. |
| bits_per_alpha_channel | int | The number of bits per Alpha channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The RGBA color. |


### get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_6}


```
 get_y_cb_cr(bits_per_sample) 
```

Gets YCbCr color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The YCbCr color. |


### get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_7}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Gets YCbCr color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_y | int | The number of bits per Y channel. |
| bits_per_cb | int | The number of bits per Cb channel. |
| bits_per_cr | int | The number of bits per Cr channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The YCbCr color. |


### get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_8}


```
 get_cmyk(bits_per_sample) 
```

Gets CMYK color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The CMYK color. |


### get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_9}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Gets CMYK color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | The number of bits per Cyan channel. |
| bits_per_magenta_channel | int | The number of bits per Magenta channel. |
| bits_per_yellow_channel | int | The number of bits per Yellow channel. |
| bits_per_key_channel | int | The number of bits per Key channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The CMYK color. |


### get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_10}


```
 get_grayscale(bits_per_sample) 
```

Gets Grayscale color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The Grayscale color. |


### get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_11}


```
 get_rgb_indexed(bits_per_sample) 
```

Gets BGRA indexed color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The BGRA color. |


### get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_12}


```
 get_bgra(bits_per_sample) 
```

Gets BGRA color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The BGRA color. |


### get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_13}


```
 get_bgr(bits_per_sample) 
```

Gets BGRA color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The BGRA color. |


### get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_14}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Gets CMYKA color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | The number of bits per Cyan channel. |
| bits_per_magenta_channel | int | The number of bits per Magenta channel. |
| bits_per_yellow_channel | int | The number of bits per Yellow channel. |
| bits_per_key_channel | int | The number of bits per Key channel. |
| bits_per_alpha_channel | int | The number of bits per Alpha channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The CMYK color. |


### get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_15}


```
 get_ycck(bits_per_sample) 
```

Gets YCCK color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | The number of bits per sample. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The YCCK color. |


### get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_16}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Gets CIE Lab color with a specified number of bits per sample.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits_per_l | int | The number of bits per L channel. |
| bits_per_a | int | The number of bits per A channel. |
| bits_per_b | int | The number of bits per B channel. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | The CIE Lab color. |


