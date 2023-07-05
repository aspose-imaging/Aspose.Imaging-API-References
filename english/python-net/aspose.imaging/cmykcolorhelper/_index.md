---
title: CmykColorHelper Class
type: docs
weight: 60
url: /python-net/aspose.imaging/cmykcolorhelper/
---

Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.CmykColorHelper

**Assembly:**  Aspose.Imaging Version: 23.6.0

The CmykColorHelper type exposes the following members:
## **Methods**
|**Name**|**Description**|
| :- | :- |
|to_cmyk(argb_pixels)|The conversion from ARGB colors to CMYK colors.|
|to_cmyk(argb_pixel)|The conversion from ARGB colors to CMYK colors.|
|to_cmyk(pixel)|The conversion from ARGB colors to CMYK colors.|
|to_cmyk(pixels)|The conversion from ARGB colors to CMYK colors.|
|to_argb(cmyk_pixels)|The conversion from CMYK colors to ARGB colors.|
|to_argb(cmyk_pixel)|The conversion from CMYK colors to ARGB colors.|
|to_argb_icc(cmyk_pixels)|  |
|to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)|  |
|to_argb_icc(cmyk_pixel)|  |
|to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)|  |
|to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(pixels)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(pixels)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(pixel)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(argb)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYK using custom ICC profiles.|
|to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|  |
|to_psd_cmyk_icc(pixels)|  |
|to_psd_cmyk_icc(argb)|  |
|to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)|  |
|get_c(cmyk)|Gets the cyan component value.|
|get_m(cmyk)|Gets the magenta component value.|
|get_y(cmyk)|Gets the yellow component value.|
|get_k(cmyk)|Gets the black component value.|
|from_components(cyan, magenta, yellow, black)|Creates CMYK from a 32-bit cyan, magenta, yellow and black values.|
|to_cmyk_array(argb_pixels)|The conversion from ARGB colors to CMYK colors.|
|to_cmyk_bytes(argb_pixels, start_index, length)|Converts ARGB to CMYK.|
|to_cmyka_bytes(argb_pixels, start_index, length)|Converts ARGB to CMYKA (with transparency).|
|to_cmyk_color(pixel)|The conversion from ARGB color to CMYK color.|
|to_cmyk_colors(pixels)|The conversion from ARGB colors to CMYK colors.|
|to_argb_colors(cmyk_pixels)|The conversion from CMYK colors to ARGB colors.|
|to_argb_color(cmyk_pixel)|The conversion from CMYK colors to ARGB colors.|
|to_argb32(cmyk_pixels)|The conversion from CMYK colors to ARGB colors.|
|to_argb_colors_with_def_icc(cmyk_pixels)|The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.|
|to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)|The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.|
|to_argb_color_with_def_icc(cmyk_pixel)|The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.|
|to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)|The conversion from CMYK color to ARGB color using Icc conversion with custom profile.|
|to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.|
|argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.|
|argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.|
|to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYK using custom ICC profiles.|
|to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)|Converts RGB to CMYKA (with alpha) using custom ICC profiles.|
|to_cmyk_array_with_def_icc(pixels)|The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.|
|argb_32_to_cmyk_array(pixels)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.|
|argb_32_to_psd_cmyk_array(pixels)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.|
|to_cmyk_with_def_icc(pixel)|The conversion from ARGB color to CMYK color using Icc conversion with default profiles.|
|argb_32_to_cmyk(argb)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.|
|argb_32_to_psd_cmyk(argb)|The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.<br/>            Uses PSD CMYK format KCMY byte order with inverted channel values.|
|to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.|
|argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.|
|argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)|The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.|
