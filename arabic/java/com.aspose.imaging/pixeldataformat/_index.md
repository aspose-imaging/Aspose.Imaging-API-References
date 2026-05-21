---
title: "PixelDataFormat"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تنسيق بيانات البكسل."
type: docs
weight: 84
url: /ar/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Grayscale](#Grayscale) | يحصل على [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) المحدد لـ 8 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في الفاصل 0-255. |
| [Grayscale16](#Grayscale16) | محدد لـ 16 بت لكل بكسل مع ما يصل إلى 16 بت تمثل شدة التدرج الرمادي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق. |
| [getCmyk()](#getCmyk--) | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من السماوي، الأرجواني، الأصفر والأسود. |
| [getCmyka()](#getCmyka--) | يحصل على acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق، ولا يتم تعريف ألفا. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف ألفا. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | يحصل على `PixelDataFormat` المحدد للون المفهرس بـ 8 بت. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | يحصل على `PixelDataFormat` المحدد للون المفهرس بـ 4 بت. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | يحصل على `PixelDataFormat` المحدد للون المفهرس بـ 2 بت. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | يحصل على `PixelDataFormat` المحدد للون المفهرس بـ 1 بت. |
| [getYCbCr()](#getYCbCr--) | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمى، فرق أزرق، فرق أحمر. |
| [getYcck()](#getYcck--) | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمى، فرق أزرق، فرق أحمر، والأسود. |
| [getRgba32Bpp()](#getRgba32Bpp--) | يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق. |
| [getRgb24BppPng()](#getRgb24BppPng--) | يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق، ولا يتم تعريف ألفا. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في الفاصل 0-255 ومكوّن ألفا إضافي بـ 8 بت. |
| [getPixelFormat()](#getPixelFormat--) | يحصل على تنسيق البكسل. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل. |
| [getChannelsCount()](#getChannelsCount--) | يحصل على عدد القنوات. |
| [getChannelBits()](#getChannelBits--) | يحصل على عدد البتات لكل قناة. |
| [getCaption()](#getCaption--) | يحصل على تسمية تنسيق بيانات البكسل. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | يحصل على اللون الرمادي مع عدد محدد من البتات لكل عينة. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | يحصل على لون RGB مع عدد محدد من البتات لكل عينة. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | يحصل على لون RGB مع عدد محدد من البتات لكل عينة. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | يحصل على لون RGBA مع عدد محدد من البتات لكل عينة. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | يحصل على لون RGBA مع عدد محدد من البتات لكل عينة. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | يحصل على لون فهرسي BGRA مع عدد محدد من البتات لكل عينة. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | يحصل على لون BGRA مع عدد محدد من البتات لكل عينة. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | يحصل على لون BGR مع عدد محدد من البتات لكل عينة. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | يحصل على لون CMYK مع عدد محدد من البتات لكل عينة. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | يحصل على لون CMYK مع عدد محدد من البتات لكل عينة. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | يحصل على لون CMYKA مع عدد محدد من البتات لكل عينة. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | يحصل على لون YCCK مع عدد محدد من البتات لكل عينة. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | يحصل على لون CIE Lab مع عدد محدد من البتات لكل عينة. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | يعيد نتيجة عدم المساواة لفئتين `PixelDataFormat`. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | يعيد نتيجة المساواة لفئتين `PixelDataFormat`. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد مساويًا لهذا المثيل. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
| [toString()](#toString--) | يعيد `System.String` التي تمثل هذا المثيل. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


يحصل على [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) المحدد لـ 8 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في الفاصل 0-255.

القيمة: الـ [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) المعرفة لـ 8 بتات لكل بكسل مع 8 بتات تمثل شدة اللون الرمادي في المجال 0-255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


محدد لـ 16 بت لكل بكسل مع ما يصل إلى 16 بت تمثل شدة التدرج الرمادي.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من السماوي، الأرجواني، الأصفر والأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


يحصل على acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


يحصل على `PixelDataFormat` المعرفة للون المفهرس 8 بت لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان. استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


يحصل على `PixelDataFormat` المعرفة للون المفهرس 4 بت لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان. استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


يحصل على `PixelDataFormat` المعرفة للون المفهرس 2 بت لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان. استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


يحصل على `PixelDataFormat` المعرفة للون المفهرس 1 بت لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يتم فيه استخدام لوحة الألوان. استخدم بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمى، فرق أزرق، فرق أحمر.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللمى، فرق أزرق، فرق أحمر، والأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


يحصل على `PixelDataFormat` المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


يحصل على `PixelDataFormat` المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، أحمر، أخضر وأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


يحصل على `PixelDataFormat` المحدد لـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في الفاصل 0-255 ومكوّن ألفا إضافي بـ 8 بت.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يحصل على تنسيق البكسل.

**Returns:**
int - تنسيق البكسل.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل.

**Returns:**
int - عدد البتات لكل بكسل.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


يحصل على عدد القنوات.

**Returns:**
int - عدد القنوات.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


يحصل على عدد البتات لكل قناة.

**Returns:**
int[] - بتات القناة.
### getCaption() {#getCaption--}
```
public String getCaption()
```


يحصل على تسمية تنسيق بيانات البكسل.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


يحصل على اللون الرمادي مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


يحصل على لون GrayscaleAlpha مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |
| alphaChannelBits | int | عدد البتات لكل عينة في قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


يحصل على لون RGB مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


يحصل على لون RGB مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerRedChannel | int | عدد البتات لكل قناة الأحمر. |
| bitsPerGreenChannel | int | عدد البتات لكل قناة الأخضر. |
| bitsPerBlueChannel | int | عدد البتات لكل قناة الأزرق. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


يحصل على لون RGBA مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


يحصل على لون RGBA مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerRedChannel | int | عدد البتات لكل قناة الأحمر. |
| bitsPerGreenChannel | int | عدد البتات لكل قناة الأخضر. |
| bitsPerBlueChannel | int | عدد البتات لكل قناة الأزرق. |
| bitsPerAlphaChannel | int | عدد البتات لكل قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


يحصل على لون فهرسي BGRA مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


يحصل على لون BGRA مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


يحصل على لون BGR مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


يحصل على لون YCbCr مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerY | int | عدد البتات لكل قناة Y. |
| bitsPerCb | int | عدد البتات لكل قناة Cb. |
| bitsPerCr | int | عدد البتات لكل قناة Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


يحصل على لون CMYK مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


يحصل على لون CMYK مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerCyanChannel | int | عدد البتات لكل قناة السيان. |
| bitsPerMagentaChannel | int | عدد البتات لكل قناة الماجنتا. |
| bitsPerYellowChannel | int | عدد البتات لكل قناة صفراء. |
| bitsPerKeyChannel | int | عدد البتات لكل قناة المفتاح. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


يحصل على لون CMYKA مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerCyanChannel | int | عدد البتات لكل قناة السيان. |
| bitsPerMagentaChannel | int | عدد البتات لكل قناة الماجنتا. |
| bitsPerYellowChannel | int | عدد البتات لكل قناة صفراء. |
| bitsPerKeyChannel | int | عدد البتات لكل قناة المفتاح. |
| bitsPerAlphaChannel | int | عدد البتات لكل قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


يحصل على لون YCCK مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البتات لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


يحصل على لون CIE Lab مع عدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerL | int | عدد البتات لكل قناة L. |
| bitsPerA | int | عدد البتات لكل قناة A. |
| bitsPerB | int | عدد البتات لكل قناة B. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


يعيد نتيجة عدم المساواة لفئتين `PixelDataFormat`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | أول `PixelDataFormat` للمقارنة. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | ثاني `PixelDataFormat` للمقارنة. |

**Returns:**
منطقي - صحيح إذا كان كل من `pixelFormat1` و `pixelFormat2` يحتويان على بيانات غير متساوية أو أحد المعلمات فارغًا.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


يعيد نتيجة المساواة لفئتين `PixelDataFormat`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | أول `PixelDataFormat` للمقارنة. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | ثاني `PixelDataFormat` للمقارنة. |

**Returns:**
منطقي - صحيح إذا كان كل من `pixelFormat1` و `pixelFormat2` يحتويان على بيانات متساوية أو كلا المعاملين فارغين.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `System.Object` المحدد مساويًا لهذا المثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للمقارنة مع هذا المثيل. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذا المثيل؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### toString() {#toString--}
```
public String toString()
```


يعيد `System.String` التي تمثل هذا المثيل.

**Returns:**
java.lang.String - `System.String` يمثل هذا المثيل.
