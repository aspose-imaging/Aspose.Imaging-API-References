---
title: "CmykColor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "لون CMYK للبكسل."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

لون CMYK للبكسل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmpty()](#getEmpty--) | يحصل على الفارغ. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | ينشئ بنية `CmykColor` من قيم سيان، ماجنتا، أصفر وأسود 32‑بت. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | التحويل من لون ARGB 32‑بت إلى CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع الملفات التعريفية الافتراضية. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | التحويل من CMYKColor إلى لون ARGB 32‑بت باستخدام تحويل icc مع الملفات التعريفية الافتراضية. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | التحويل من ARGB 32‑بت إلى CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | التحويل من CMYKColor إلى Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع الملفات التعريفية الافتراضية. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع الملفات التعريفية الافتراضية. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | التحويل من CMYKColor إلى Color باستخدام تحويل icc. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | التحويل من CMYKColor إلى Color باستخدام تحويل icc. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | يحصل على قيمة مكوّن السيان في بنية `com.com.aspose.imaging.Color` هذه. |
| [getM()](#getM--) | يحصل على قيمة مكوّن الماجنتا في بنية `com.com.aspose.imaging.Color` هذه. |
| [getY()](#getY--) | يحصل على قيمة مكوّن الأصفر في بنية `com.com.aspose.imaging.Color` هذه. |
| [getK()](#getK--) | يحصل على قيمة مكوّن الأسود في بنية `com.com.aspose.imaging.Color` هذه. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا الهيكل `com.com.aspose.imaging.Color` غير مهيأ. |
| [hashCode()](#hashCode--) | دالة الحصول على قيمة التجزئة. |
| [toValue()](#toValue--) | القيمة إلى. |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.imaging.CmykColor-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


يحصل على الفارغ.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


ينشئ هيكل `CmykColor` من قيم السيان، الماجنتا، الأصفر والأسود 32‑بت. هذه الطريقة مهجورة. يرجى استخدام CmykColorHelper\#fromComponents(int, int, int, int) الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سماوي | int | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| ماجنتا | int | المكوّن الماجنتا. القيم الصالحة هي من 0 إلى 255. |
| أصفر | int | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | int | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


التحويل من لون ARGB 32‑بت إلى CMYKColor. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toCmyk(int[])` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | البكسلات بتنسيق ARGB 32‑بت. |

**Returns:**
com.aspose.imaging.CmykColor[] - الـ [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\} الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns:**
com.aspose.imaging.Color[] - المصفوفة الخاصة بألوان ARGB.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


التحويل من CMYKColor إلى لون ARGB 32‑بت باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toArgb32(int[])` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns:**
int[] - المصفوفة الخاصة بلون ARGB 32‑بت.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


التحويل من ARGB 32‑بت إلى CMYKColor. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toCmyk(int)` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixel | int | البكسل بتنسيق ARGB 32‑بت. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


التحويل من CMYKColor إلى Color. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toArgb(int)` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام CmykColorHelper\#toArgbIcc(int[]) الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | البكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns:**
com.aspose.imaging.Color[] - الـ `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toArgbIcc(int)` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | البكسل من نوع CMYKColor بتنسيق CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من CMYKColor إلى Color باستخدام تحويل icc. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | البكسلات من نوع CMYKColor بتنسيق CMYK. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns:**
com.aspose.imaging.Color[] - الـ `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من CMYKColor إلى Color باستخدام تحويل icc. هذه الطريقة مهجورة. يرجى استخدام `CmykColorHelper.toArgbIcc(int, Stream, Stream)` الأكثر فاعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | البكسل من نوع CMYKColor بتنسيق CMYK. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


يحصل على قيمة مكوّن السيان في بنية `com.com.aspose.imaging.Color` هذه.

**Returns:**
byte - قيمة مكوّن السيان لهذا `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


يحصل على قيمة مكوّن الماجنتا في بنية `com.com.aspose.imaging.Color` هذه.

**Returns:**
byte - قيمة مكوّن الماجنتا لهذا `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


يحصل على قيمة مكوّن الأصفر في بنية `com.com.aspose.imaging.Color` هذه.

**Returns:**
byte - قيمة مكوّن الأصفر لهذا `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


يحصل على قيمة مكوّن الأسود في بنية `com.com.aspose.imaging.Color` هذه.

القيمة: قيمة مكوّن الأسود لهذا `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الهيكل `com.com.aspose.imaging.Color` غير مهيأ.

**Returns:**
boolean - تُعيد هذه الخاصية true إذا كان هذا اللون غير مبدئ؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


دالة الحصول على قيمة التجزئة.

**Returns:**
int - الـ `int`.
### toValue() {#toValue--}
```
public long toValue()
```


القيمة إلى.

**Returns:**
long - القيمة الطويلة لـ CMYK.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
