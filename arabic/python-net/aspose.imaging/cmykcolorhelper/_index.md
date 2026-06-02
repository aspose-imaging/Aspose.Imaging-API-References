---
title: "فئة CmykColorHelper"
type: docs
weight: 1140
url: /ar/python-net/aspose.imaging/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) struct.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColorHelper

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [argb_32_to_cmyk(argb)](#argb_32_to_cmyk_argb_1) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [argb_32_to_cmyk_array(pixels)](#argb_32_to_cmyk_array_pixels_2) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [argb_32_to_psd_cmyk(argb)](#argb_32_to_psd_cmyk_argb_5) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [argb_32_to_psd_cmyk_array(pixels)](#argb_32_to_psd_cmyk_array_pixels_6) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_9) | ينشئ CMYK من قيم السينا، الماجنتا، الأصفر والأسود ذات 32 بت. |
| [get_c(cmyk)](#get_c_cmyk_10) | يحصل على قيمة مكوّن السينا. |
| [get_k(cmyk)](#get_k_cmyk_11) | يحصل على قيمة مكوّن الأسود. |
| [get_m(cmyk)](#get_m_cmyk_12) | يحصل على قيمة مكوّن الماجنتا. |
| [get_y(cmyk)](#get_y_cmyk_13) | يحصل على قيمة مكوّن الأصفر. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_14) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_15) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_16) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb_color(cmyk_pixel)](#to_argb_color_cmyk_pixel_17) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb_color_with_def_icc(cmyk_pixel)](#to_argb_color_with_def_icc_cmyk_pixel_18) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص. |
| [to_argb_colors(cmyk_pixels)](#to_argb_colors_cmyk_pixels_20) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb_colors_with_def_icc(cmyk_pixels)](#to_argb_colors_with_def_icc_cmyk_pixels_21) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_23) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_25) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_27) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_28) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_29) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_30) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk_array(argb_pixels)](#to_cmyk_array_argb_pixels_31) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk_array_with_def_icc(pixels)](#to_cmyk_array_with_def_icc_pixels_32) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_34) | يحوّل ARGB إلى CMYK. |
| [to_cmyk_color(pixel)](#to_cmyk_color_pixel_35) | التحويل من لون ARGB إلى لون CMYK. |
| [to_cmyk_colors(pixels)](#to_cmyk_colors_pixels_36) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk_icc(argb)](#to_cmyk_icc_argb_37) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_39) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_41) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_42) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45) | يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة. |
| [to_cmyk_with_def_icc(pixel)](#to_cmyk_with_def_icc_pixel_46) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyka_bytes(argb_pixels, start_index, length)](#to_cmyka_bytes_argb_pixels_start_index_length_48) | يحوّل ARGB إلى CMYKA (مع الشفافية). |
| [to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49) | يقوم بتحويل RGB إلى CMYKA (مع قناة ألفا) باستخدام ملفات تعريف ICC مخصصة. |
| [to_psd_cmyk_icc(argb)](#to_psd_cmyk_icc_argb_50) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [to_psd_cmyk_icc(pixels)](#to_psd_cmyk_icc_pixels_52) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| [to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |


### Method: argb_32_to_cmyk(argb)  [static] {#argb_32_to_cmyk_argb_1}


```
 argb_32_to_cmyk(argb) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: argb_32_to_cmyk_array(pixels)  [static] {#argb_32_to_cmyk_array_pixels_2}


```
 argb_32_to_cmyk_array(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_3}


```
 argb_32_to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_cmyk_with_icc_argb_rgb_icc_stream_cmyk_icc_stream_4}


```
 argb_32_to_cmyk_with_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: argb_32_to_psd_cmyk(argb)  [static] {#argb_32_to_psd_cmyk_argb_5}


```
 argb_32_to_psd_cmyk(argb) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة. |


### Method: argb_32_to_psd_cmyk_array(pixels)  [static] {#argb_32_to_psd_cmyk_array_pixels_6}


```
 argb_32_to_psd_cmyk_array(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


### Method: argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_7}


```
 argb_32_to_psd_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


### Method: argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#argb_32_to_psd_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_8}


```
 argb_32_to_psd_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | int | لون ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_9}


```
 from_components(cyan, magenta, yellow, black) 
```

ينشئ CMYK من قيم السينا، الماجنتا، الأصفر والأسود ذات 32 بت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| سماوي | int | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| أرجواني | int | المكوّن الأرجواني. القيم الصالحة هي من 0 إلى 255. |
| أصفر | int | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | int | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_10}


```
 get_c(cmyk) 
```

يحصل على قيمة مكوّن السينا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة المكوّن السماوي. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_k(cmyk)  [static] {#get_k_cmyk_11}


```
 get_k(cmyk) 
```

يحصل على قيمة مكوّن الأسود.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأسود. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_m(cmyk)  [static] {#get_m_cmyk_12}


```
 get_m(cmyk) 
```

يحصل على قيمة مكوّن الماجنتا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأرجواني. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: get_y(cmyk)  [static] {#get_y_cmyk_13}


```
 get_y(cmyk) 
```

يحصل على قيمة مكوّن الأصفر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأصفر. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_14}


```
 to_argb(cmyk_pixel) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_15}


```
 to_argb(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_16}


```
 to_argb32(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان ARGB المقدمة كقيم صحيحة 32-بت. |


### Method: to_argb_color(cmyk_pixel)  [static] {#to_argb_color_cmyk_pixel_17}


```
 to_argb_color(cmyk_pixel) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_color_with_def_icc(cmyk_pixel)  [static] {#to_argb_color_with_def_icc_cmyk_pixel_18}


```
 to_argb_color_with_def_icc(cmyk_pixel) 
```

التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | لون ARGB. |


### Method: to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_color_with_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_19}


```
 to_argb_color_with_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | لون ARGB. |


### Method: to_argb_colors(cmyk_pixels)  [static] {#to_argb_colors_cmyk_pixels_20}


```
 to_argb_colors(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_colors_with_def_icc(cmyk_pixels)  [static] {#to_argb_colors_with_def_icc_cmyk_pixels_21}


```
 to_argb_colors_with_def_icc(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | بكسلات CMYK المقدمة كقيم صحيحة 32-بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_22}


```
 to_argb_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_23}


```
 to_argb_icc(cmyk_pixel) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_24}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_25}


```
 to_argb_icc(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | بكسلات CMYK المقدمة كقيم صحيحة 32-بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_26}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_27}


```
 to_cmyk(argb_pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_28}


```
 to_cmyk(argb_pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | ألوان ARGB المقدمة كقيم صحيحة 32-بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |



**See also:**

**[Example # 1](#example_178)**: The following example shows how to convert RGB colors to their CMYK counterpa...


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_29}


```
 to_cmyk(pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |



**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_30}


```
 to_cmyk(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_array(argb_pixels)  [static] {#to_cmyk_array_argb_pixels_31}


```
 to_cmyk_array(argb_pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | ألوان ARGB المقدمة كقيم صحيحة 32-بت. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_array_with_def_icc(pixels)  [static] {#to_cmyk_array_with_def_icc_pixels_32}


```
 to_cmyk_array_with_def_icc(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_array_with_icc_pixels_rgb_icc_stream_cmyk_icc_stream_33}


```
 to_cmyk_array_with_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_34}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

يحوّل ARGB إلى CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | ألوان RGB المقدمة كقيم صحيحة 32-بت. |
| start_index | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB التي سيتم تحويلها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | ألوان CMYK المقدمة كمصفوفة بايت. |


### Method: to_cmyk_color(pixel)  [static] {#to_cmyk_color_pixel_35}


```
 to_cmyk_color(pixel) 
```

التحويل من لون ARGB إلى لون CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: to_cmyk_colors(pixels)  [static] {#to_cmyk_colors_pixels_36}


```
 to_cmyk_colors(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(argb)  [static] {#to_cmyk_icc_argb_37}


```
 to_cmyk_icc(argb) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_argb_rgb_icc_stream_cmyk_icc_stream_38}


```
 to_cmyk_icc(argb, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_39}


```
 to_cmyk_icc(pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_40}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_41}


```
 to_cmyk_icc(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_42}


```
 to_cmyk_icc(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_43}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_44}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_45}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان RGB المقدمة كقيم صحيحة 32-بت. |
| start_index | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB التي سيتم تحويلها. |
| rgb_icc_stream | _io.BufferedRandom | دفق ملف تعريف RGB. |
| cmyk_icc_stream | _io.BufferedRandom | دفق ملف تعريف CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | ألوان CMYK المقدمة كمصفوفة بايت. |


### Method: to_cmyk_with_def_icc(pixel)  [static] {#to_cmyk_with_def_icc_pixel_46}


```
 to_cmyk_with_def_icc(pixel) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_with_icc_pixel_rgb_icc_stream_cmyk_icc_stream_47}


```
 to_cmyk_with_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/imaging/python-net/aspose.imaging/color/) | لون ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت. |


### Method: to_cmyka_bytes(argb_pixels, start_index, length)  [static] {#to_cmyka_bytes_argb_pixels_start_index_length_48}


```
 to_cmyka_bytes(argb_pixels, start_index, length) 
```

يحوّل ARGB إلى CMYKA (مع الشفافية).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | ألوان RGB المقدمة كقيم صحيحة 32-بت. |
| start_index | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB التي سيتم تحويلها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | ألوان CMYK المقدمة كمصفوفة بايت. |


### Method: to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyka_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_49}


```
 to_cmyka_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

يقوم بتحويل RGB إلى CMYKA (مع قناة ألفا) باستخدام ملفات تعريف ICC مخصصة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان RGB المقدمة كقيم صحيحة 32-بت. |
| start_index | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB التي سيتم تحويلها. |
| rgb_icc_stream | _io.BufferedRandom | دفق ملف تعريف RGB. |
| cmyk_icc_stream | _io.BufferedRandom | دفق ملف تعريف CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | ألوان CMYK المقدمة كمصفوفة بايت. |


### Method: to_psd_cmyk_icc(argb)  [static] {#to_psd_cmyk_icc_argb_50}


```
 to_psd_cmyk_icc(argb) 
```

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | int | لون ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | لون CMYK معروض كقيمة عدد صحيح 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة. |


### Method: to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_51}


```
 to_psd_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pixel | int |  |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


### Method: to_psd_cmyk_icc(pixels)  [static] {#to_psd_cmyk_icc_pixels_52}


```
 to_psd_cmyk_icc(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


### Method: to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_psd_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_53}


```
 to_psd_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.<br/>            يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البكسلات | int[] | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف RGB ICC. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف CMYK ICC. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | ألوان CMYK معروضة كقيم أعداد صحيحة 32‑بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.. |


## **Examples**
### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# احصل على تمثيل صحيح للون الأسود في مساحة ألوان CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# المربع الأسود.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# ارسم المربع الأسود في مركز الصورة.
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

# المخرجات تبدو هكذا:
# حوّل RGB إلى CMYK دون استخدام ملفات تعريف ICC.
# RGB(255,0,0)		=> CMYK(0,255,255,0)
# RGB(0,128,0)		=> CMYK(255,0,255,127)
# RGB(0,0,255)		=> CMYK(255,255,0,0)


```

