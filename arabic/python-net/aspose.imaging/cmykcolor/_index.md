---
title: "الفئة CmykColor"
type: docs
weight: 1130
url: /ar/python-net/aspose.imaging/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CmykColor

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | يُنشئ مثيلًا جديدًا من فئة CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| c | System.Byte | r | يحصل على قيمة المكوّن السماوي لهذا الهيكل [Color](/imaging/python-net/aspose.imaging/color/). |
| empty [static] | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | r | يحصل على القيمة الفارغة. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الهيكل [Color](/imaging/python-net/aspose.imaging/color/) غير مهيأ. |
| k | System.Byte | r | يحصل على قيمة المكوّن الأسود لهذا الهيكل [Color](/imaging/python-net/aspose.imaging/color/). |
| m | System.Byte | r | يحصل على قيمة المكوّن الأرجواني لهذا الهيكل [Color](/imaging/python-net/aspose.imaging/color/). |
| y | System.Byte | r | يحصل على قيمة المكوّن الأصفر لهذا الهيكل [Color](/imaging/python-net/aspose.imaging/color/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | ينشئ هيكلًا من نوع [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) من قيم 32‑بت للسماوي، الأرجواني، الأصفر والأسود.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | التحويل من CMYKColor إلى لون ARGB 32‑بت باستخدام تحويل icc مع ملفات التعريف الافتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية. |
| [to_cmyk_color(argb_pixel)](#to_cmyk_color_argb_pixel_5) | التحويل من 32-bit ARGB إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_cmyk_colors(argb_pixels)](#to_cmyk_colors_argb_pixels_6) | التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_7) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_8) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_9) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_11) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_with_def_icc(cmyk_pixels)](#to_color_with_def_icc_cmyk_pixels_13) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_colors(cmyk_pixels)](#to_colors_cmyk_pixels_15) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_colors_with_def_icc(cmyk_pixels)](#to_colors_with_def_icc_cmyk_pixels_16) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية. |
| [to_value()](#to_value__18) | القيمة إلى. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

يُنشئ مثيلًا جديدًا من فئة CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

ينشئ هيكلًا من نوع [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) من قيم 32‑بت للسماوي، الأرجواني، الأصفر والأسود.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية.

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
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | الـ[CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

التحويل من CMYKColor إلى لون ARGB 32‑بت باستخدام تحويل icc مع ملفات التعريف الافتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb32(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | المصفوفة الخاصة بلون ARGB 32-bit. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | الـ[CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | البكسلات بتنسيق ARGB 32-bit. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | الـ[CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_color(argb_pixel)  [static] {#to_cmyk_color_argb_pixel_5}


```
 to_cmyk_color(argb_pixel) 
```

التحويل من 32-bit ARGB إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixel | int | البكسل بتنسيق ARGB 32-bit. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | الـ[CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_cmyk_colors(argb_pixels)  [static] {#to_cmyk_colors_argb_pixels_6}


```
 to_cmyk_colors(argb_pixels) 
```

التحويل من لون ARGB 32‑بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb_pixels | int[] | البكسلات بتنسيق ARGB 32-bit. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | الـ[CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/). |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_7}


```
 to_color(cmyk_pixel) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | المصفوفة الخاصة بألوان ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_8}


```
 to_color(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | المصفوفة الخاصة بألوان ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_9}


```
 to_color_icc(cmyk_pixel) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) |  |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_11}


```
 to_color_icc(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_def_icc(cmyk_pixels)  [static] {#to_color_with_def_icc_cmyk_pixels_13}


```
 to_color_with_def_icc(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixel)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسل من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | الـ [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_14}


```
 to_color_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسل من نوع CMYKColor بتنسيق CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | الـ [Color](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors(cmyk_pixels)  [static] {#to_colors_cmyk_pixels_15}


```
 to_colors(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | المصفوفة الخاصة بألوان ARGB. |


### Method: to_colors_with_def_icc(cmyk_pixels)  [static] {#to_colors_with_def_icc_cmyk_pixels_16}


```
 to_colors_with_def_icc(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_colors_with_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_17}


```
 to_colors_with_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](/imaging/python-net/aspose.imaging/cmykcolorhelper/) الأكثر فعالية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | البكسلات من نوع CMYKColor بتنسيق CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | الـ [Color[]](/imaging/python-net/aspose.imaging/color/). |


### Method: to_value() {#to_value__18}


```
 to_value() 
```

القيمة إلى.

**Returns**

| نوع | الوصف |
| :- | :- |
| int | القيمة الطويلة لـ CMYK. |


