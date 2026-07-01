---
title: "BitmapInfoHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد BITMAPINFOHEADER."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

يحدد BITMAPINFOHEADER. دعم نظام التشغيل: Windows NT، 3.1x أو أحدث. الميزات: يضيف صيغ 16 بت لكل بكسل و 32 بت لكل بكسل. يضيف ضغط RLE.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | يحصل على ضغط الصورة النقطية. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | يضبط ضغط الصورة النقطية. |
| [getBitmapImageSize()](#getBitmapImageSize--) | يحصل على حجم البيانات الخام للصورة النقطية بالبايت. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | يضبط حجم البيانات الخام للصورة النقطية بالبايت. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | يحصل على دقة البكسلات الأفقية. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | يحصل أو يضبط دقة البكسلات الأفقية. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | يحصل أو يضبط دقة البكسلات العمودية. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | يحصل أو يضبط دقة البكسلات العمودية. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | يحصل على عدد ألوان اللوحة المستخدمة. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | يحصل أو يضبط عدد ألوان اللوحة المستخدمة. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | يحصل أو يضبط عدد ألوان اللوحة المهمة. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | يحصل أو يضبط عدد ألوان اللوحة المهمة. |
| [getExtraBitMasks()](#getExtraBitMasks--) | يحصل أو يضبط أقنعة البت الإضافية. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | يحصل أو يضبط أقنعة البت الإضافية. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


يحصل على ضغط الصورة النقطية.

**Returns:**
long - ضغط الصورة النقطية.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


يضبط ضغط الصورة النقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | ضغط الصورة النقطية. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


يحصل على حجم البيانات الخام للصورة النقطية بالبايت.

**Returns:**
long - حجم البيانات الخام للصورة النقطية بالبايت.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


يضبط حجم البيانات الخام للصورة النقطية بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | حجم البيانات الخام للـ bitmap بالبايت. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


يحصل على دقة البكسلات الأفقية.

**Returns:**
int - دقة البكسلات الأفقية.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


يحصل أو يضبط دقة البكسلات الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | دقة البكسلات الأفقية. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


يحصل أو يضبط دقة البكسلات العمودية.

**Returns:**
int - دقة البكسلات العمودية.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


يحصل أو يضبط دقة البكسلات العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | دقة البكسلات العمودية. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


يحصل على عدد ألوان اللوحة المستخدمة.

**Returns:**
long - عدد ألوان لوحة الألوان المستخدمة.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


يحصل أو يضبط عدد ألوان اللوحة المستخدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | عدد ألوان لوحة الألوان المستخدمة. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


يحصل أو يضبط عدد ألوان اللوحة المهمة.

**Returns:**
long - عدد ألوان لوحة الألوان المهمة.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


يحصل أو يضبط عدد ألوان اللوحة المهمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | عدد ألوان لوحة الألوان المهمة. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


يحصل أو يضبط أقنعة البت الإضافية. تكون موجودة فقط في حالة أن رأس DIB هو BITMAPINFOHEADER وأن `BitmapCompression` مضبوط إما على `BitmapCompression.Bitfields` (RGB) أو `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - أقنعة البت الإضافية.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


يحصل أو يضبط أقنعة البت الإضافية. تكون موجودة فقط في حالة أن رأس DIB هو BITMAPINFOHEADER وأن `BitmapCompression` مضبوط إما على `BitmapCompression.Bitfields` (RGB) أو `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | أقنعة البت الإضافية. |

