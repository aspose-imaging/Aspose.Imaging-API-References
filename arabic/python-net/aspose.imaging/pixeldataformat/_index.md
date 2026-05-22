---
title: "فئة PixelDataFormat"
type: docs
weight: 6920
url: /ar/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | معرف بـ 16 بت لكل بكسل مع ما يصل إلى 16 بت تمثل شدة التدرج الرمادي. |
| bits_per_pixel | int | r | يحصل على عدد البتات لكل بكسل. |
| التسمية | string | r | يحصل على تسمية تنسيق بيانات البكسل. |
| channel_bits | int[] | r | يحصل على عدد البتات لكل قناة. |
| channels_count | int | r | يحصل على عدد القنوات. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المعرفة بـ 32 بت لكل بكسل مع 8 بت لكل من السماوي، الأرجواني، الأصفر والأسود. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على acmyk. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المعرفة بـ 8 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المعرفة بـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255 ومكوّن ألفا إضافي بــ 8 بت. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | يحصل على تنسيق البكسل. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المعرفة بـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر، الأخضر والأزرق، ولا يتم تعريف الألفا. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المعرفة بـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف الألفا. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد للون المفهرس ببت واحد لكل لون.<br/>            تخزين بيانات البكسل المفهرسة يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان.<br/>            استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج لون مفهرس. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد للون المفهرس ببتين لكل لون.<br/>            تخزين بيانات البكسل المفهرسة يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان.<br/>            استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج لون مفهرس. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد للون المفهرس بأربع بتات لكل لون.<br/>            تخزين بيانات البكسل المفهرسة يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان.<br/>            استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج لون مفهرس. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد للون المفهرس بثمانية بتات لكل لون.<br/>            تخزين بيانات البكسل المفهرسة يهدف إلى السماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان.<br/>            استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج لون مفهرس. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللومي، الفرق الأزرق والفرق الأحمر. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | يحصل على [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللومي، الفرق الأزرق، الفرق الأحمر، ومكوّن اللون الأسود. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | يحصل على لون BGRA مع عدد محدد من البتات لكل عينة. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | يحصل على لون BGRA مع عدد محدد من البتات لكل عينة. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | يحصل على لون CIE Lab مع عدد محدد من البتات لكل عينة. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | يحصل على لون CMYK مع عدد محدد من البتات لكل عينة. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | يحصل على لون CMYK مع عدد محدد من البتات لكل عينة. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | يحصل على لون CMYKA مع عدد محدد من البتات لكل عينة. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | يحصل على لون Grayscale مع عدد محدد من البتات لكل عينة. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | يحصل على لون RGB مع عدد محدد من البتات لكل عينة. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | يحصل على لون RGB مع عدد محدد من البتات لكل عينة. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | يحصل على لون BGRA المفهرس مع عدد محدد من البتات لكل عينة. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | يحصل على لون RGBA مع عدد محدد من البتات لكل عينة. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | يحصل على لون RGBA مع عدد محدد من البتات لكل عينة. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | يحصل على لون YCCK مع عدد محدد من البتات لكل عينة. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

يحصل على لون BGRA مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون BGRA. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

يحصل على لون BGRA مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون BGRA. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

يحصل على لون CIE Lab مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_l | int | عدد البتات لكل قناة L. |
| bits_per_a | int | عدد البتات لكل قناة A. |
| bits_per_b | int | عدد البتات لكل قناة B. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون CIE Lab. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

يحصل على لون CMYK مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_cyan_channel | int | عدد البتات لكل قناة Cyan. |
| bits_per_magenta_channel | int | عدد البتات لكل قناة Magenta. |
| bits_per_yellow_channel | int | عدد البتات لكل قناة Yellow. |
| bits_per_key_channel | int | عدد البتات لكل قناة Key. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون CMYK. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

يحصل على لون CMYK مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون CMYK. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

يحصل على لون CMYKA مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_cyan_channel | int | عدد البتات لكل قناة Cyan. |
| bits_per_magenta_channel | int | عدد البتات لكل قناة Magenta. |
| bits_per_yellow_channel | int | عدد البتات لكل قناة Yellow. |
| bits_per_key_channel | int | عدد البتات لكل قناة Key. |
| bits_per_alpha_channel | int | عدد البتات لكل قناة Alpha. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون CMYK. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

يحصل على لون Grayscale مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون التدرج الرمادي. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون GrayscaleAlpha. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |
| alpha_channel_bits | int | عدد البتات لكل عينة في قناة Alpha. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون GrayscaleAlpha. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

يحصل على لون RGB مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_red_channel | int | عدد البتات لكل قناة Red. |
| bits_per_green_channel | int | عدد البتات لكل قناة Green. |
| bits_per_blue_channel | int | عدد البتات لكل قناة Blue. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون RGB. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

يحصل على لون RGB مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون RGB. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

يحصل على لون BGRA المفهرس مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون BGRA. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

يحصل على لون RGBA مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_red_channel | int | عدد البتات لكل قناة Red. |
| bits_per_green_channel | int | عدد البتات لكل قناة Green. |
| bits_per_blue_channel | int | عدد البتات لكل قناة Blue. |
| bits_per_alpha_channel | int | عدد البتات لكل قناة Alpha. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون RGBA. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

يحصل على لون RGBA مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون RGBA. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون YCbCr. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_y | int | عدد البتات لكل قناة Y. |
| bits_per_cb | int | عدد البتات لكل قناة Cb. |
| bits_per_cr | int | عدد البتات لكل قناة Cr. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون YCbCr. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

يحصل على لون YCCK مع عدد محدد من البتات لكل عينة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bits_per_sample | int | عدد البتات لكل عينة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | لون YCCK. |


