---
title: PixelDataFormat Class
type: docs
weight: 660
url: /python-net/api-reference/aspose.imaging/pixeldataformat/
---

The pixel data format. This is an immutable object.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.PixelDataFormat

**Assembly:**  Aspose.Imaging Version: 23.3.0

The PixelDataFormat type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|rgb_32_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.|
|cmyk|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.|
|cmyka|Gets the acmyk.|
|rgb_24_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.|
|rgb_16_bpp_555|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.|
|rgb_16_bpp_565|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.|
|rgb_indexed_8_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for indexed 8 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.|
|rgb_indexed_4_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for indexed 4 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.|
|rgb_indexed_2_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for indexed 2 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.|
|rgb_indexed_1_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for indexed 1 bit per color.<br/>            The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used.<br/>            Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.|
|y_cb_cr|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.|
|grayscale|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.|
|ycck|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.|
|rgba_32_bpp|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.|
|rgb_24_bpp_png|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.|
|grayscale_alpha|Gets the [PixelDataFormat](/imaging/python-net/api-reference/aspose.imaging/pixeldataformat/) defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.|
|pixel_format|Gets the pixel format.|
|bits_per_pixel|Gets the bits per pixel.|
|channels_count|Gets the channels count.|
|channel_bits|Gets the bits count for each channel.|
|caption|Gets the pixel data format caption.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_grayscale_alpha(bits_per_sample)|Gets GrayscaleAlpha color with a specified number of bits per sample.|
|get_grayscale_alpha(bits_per_sample, alpha_channel_bits)|Gets GrayscaleAlpha color with a specified number of bits per sample.|
|get_rgb(bits_per_sample)|Gets RGB color with a specified number of bits per sample.|
|get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)|Gets RGB color with a specified number of bits per sample.|
|get_rgba(bits_per_sample)|Gets RGBA color with a specified number of bits per sample.|
|get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)|Gets RGBA color with a specified number of bits per sample.|
|get_y_cb_cr(bits_per_sample)|Gets YCbCr color with a specified number of bits per sample.|
|get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)|Gets YCbCr color with a specified number of bits per sample.|
|get_cmyk(bits_per_sample)|Gets CMYK color with a specified number of bits per sample.|
|get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)|Gets CMYK color with a specified number of bits per sample.|
|get_grayscale(bits_per_sample)|Gets Grayscale color with a specified number of bits per sample.|
|get_rgb_indexed(bits_per_sample)|Gets BGRA indexed color with a specified number of bits per sample.|
|get_bgra(bits_per_sample)|Gets BGRA color with a specified number of bits per sample.|
|get_bgr(bits_per_sample)|Gets BGRA color with a specified number of bits per sample.|
|get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)|Gets CMYKA color with a specified number of bits per sample.|
|get_ycck(bits_per_sample)|Gets YCCK color with a specified number of bits per sample.|
|get_cie_lab(bits_per_l, bits_per_a, bits_per_b)|Gets CIE Lab color with a specified number of bits per sample.|
