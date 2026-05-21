---
title: "CmykColorHelper"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح 32-بت موقعة."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح 32-بت موقعة. يوفر واجهة برمجة تطبيقات مشابهة للهيكل [CmykColor](../../com.aspose.imaging/cmykcolor). إنه أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الثابتة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل [CmykColor](../../com.aspose.imaging/cmykcolor) المهمل.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | يحصل على قيمة المكوّن السيان. |
| [getM(int cmyk)](#getM-int-) | يحصل على قيمة المكوّن الماجنتا. |
| [getY(int cmyk)](#getY-int-) | يحصل على قيمة المكوّن الأصفر. |
| [getK(int cmyk)](#getK-int-) | يحصل على قيمة المكوّن الأسود. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | ينشئ CMYK من قيم السيان والماجنتا والأصفر والأسود 32-بت. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | يحوّل ARGB إلى CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | يحوّل ARGB إلى CMYKA (مع الشفافية). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | التحويل من لون ARGB إلى لون CMYK. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | التحويل من لون ARGB إلى لون CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [toArgb(int cmykPixel)](#toArgb-int-) | التحويل من لون CMYK إلى لون ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | يُجري التحويل من ألوان CMYK إلى ألوان ARGB ويخزنها في نفس المصفوفة إذا كان `reuseArray` صحيحًا. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | يحوّل RGB إلى CMYK باستخدام ملفات ICC مخصصة. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | يحوّل RGB إلى CMYK باستخدام ملفات ICC مخصصة. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | يحوّل RGB إلى CMYKA (مع ألفا) باستخدام ملفات ICC مخصصة. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | يحوّل RGB إلى CMYKA (مع ألفا) باستخدام ملفات ICC مخصصة. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


يحصل على قيمة المكوّن السيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة مكوّن السماوي.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//المخرجات تبدو هكذا:
//حوّل RGB إلى CMYK دون استخدام ملفات ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


يحصل على قيمة المكوّن الماجنتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة مكوّن الماجنتا.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//المخرجات تبدو هكذا:
//حوّل RGB إلى CMYK دون استخدام ملفات ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


يحصل على قيمة المكوّن الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة مكوّن الأصفر.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//المخرجات تبدو هكذا:
//حوّل RGB إلى CMYK دون استخدام ملفات ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


يحصل على قيمة المكوّن الأسود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة مكوّن الأسود.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//المخرجات تبدو هكذا:
//حوّل RGB إلى CMYK دون استخدام ملفات ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


ينشئ CMYK من قيم السيان والماجنتا والأصفر والأسود 32-بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سماوي | int | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| ماجنتا | int | المكوّن الماجنتا. القيم الصالحة هي من 0 إلى 255. |
| أصفر | int | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | int | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//المخرجات تبدو هكذا:
//حوّل CMYK إلى RGB دون استخدام ملفات تعريف ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | ألوان ARGB الممثّلة كقيم عدد صحيح 32-بت. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


يحوّل ARGB إلى CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


يحوّل ARGB إلى CMYKA (مع الشفافية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


التحويل من لون ARGB إلى لون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixel | int | لون ARGB المقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


التحويل من لون ARGB إلى لون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | لون ARGB. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//المخرجات تبدو هكذا:
//حوّل RGB إلى CMYK دون استخدام ملفات ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK المقدمة كقيم عدد صحيح 32-بت. |

**Returns:**
com.aspose.imaging.Color[] - ألوان ARGB.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


التحويل من لون CMYK إلى لون ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//المخرجات تبدو هكذا:
//حوّل CMYK إلى RGB دون استخدام ملفات تعريف ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK المقدمة كقيم عدد صحيح 32-بت. |

**Returns:**
int[] - ألوان ARGB المقدمة كقيم عدد صحيح 32-بت.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


يُجري التحويل من ألوان CMYK إلى ألوان ARGB ويخزنها في نفس المصفوفة إذا كان `reuseArray` صحيحًا. وإلا، سيتم تخصيص مصفوفة جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK المقدمة كقيم عدد صحيح 32-بت. |
| reuseArray | boolean | إذا كان `true` فسيتم إعادة ملء مصفوفة `cmykPixels` المدخلة بقيم جديدة وإرجاعها؛ وإلا سيتم تخصيص مصفوفة جديدة وإرجاعها. |

**Returns:**
int[] - المصفوفة الجديدة المخصصة أو `cmykPixels` المملوءة بألوان ARGB المقدمة كقيم عدد صحيح 32-بت.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | بكسلات CMYK المقدمة كقيم عدد صحيح 32-بت. |

**Returns:**
com.aspose.imaging.Color[] - ألوان ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK المقدمة كقيم عدد صحيح 32-بت. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

**Returns:**
com.aspose.imaging.Color[] - ألوان ARGB.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// حدد المسار إلى ملفات تعريف ICC المخصصة لـ RGB و CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// اقرأ جميع البايتات من ملفات ICC إلى الذاكرة لتتمكن من إعادة ضبط دفق ملف تعريف الإدخال قبل استدعاء toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//المخرجات تبدو هكذا:
//حوّل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC مخصصة.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// حدد المسار إلى ملفات تعريف ICC المخصصة لـ RGB و CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// اقرأ جميع البايتات من ملفات ICC إلى الذاكرة لتتمكن من إعادة ضبط دفق ملف تعريف الإدخال قبل استدعاء toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//المخرجات تبدو هكذا:
//حوّل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC مخصصة.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ألوان ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


يحوّل RGB إلى CMYK باستخدام ملفات ICC مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |
| rgbIccStream | java.io.InputStream | دفق ملف تعريف RGB. |
| cmykIccStream | java.io.InputStream | دفق ملف تعريف CMYK. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


يحوّل RGB إلى CMYK باستخدام ملفات ICC مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |
| cmykBytes | byte[] | بايتات Cmyk. |
| cmykOffset | int | إزاحة `cmykBytes`. |
| rgbIccStream | java.io.InputStream | دفق ملف تعريف RGB. |
| cmykIccStream | java.io.InputStream | دفق ملف تعريف CMYK. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


يحوّل RGB إلى CMYKA (مع ألفا) باستخدام ملفات ICC مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |
| cmykBytes | byte[] | بايتات Cmyk. |
| cmykOffset | int | إزاحة `cmykBytes`. |
| rgbIccStream | java.io.InputStream | دفق ملف تعريف RGB. |
| cmykIccStream | java.io.InputStream | دفق ملف تعريف CMYK. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int[] - ألوان CMYK المقدمة كقيم صحيحة 32-بت بترتيب بايت KCMY مع قيم قنوات مقلوبة.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


يحوّل RGB إلى CMYKA (مع ألفا) باستخدام ملفات ICC مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان RGB الممثّلة كقيم عدد صحيح 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |
| rgbIccStream | java.io.InputStream | دفق ملف تعريف RGB. |
| cmykIccStream | java.io.InputStream | دفق ملف تعريف CMYK. |

**Returns:**
byte[] - ألوان CMYK المقدمة كمصفوفة بايت.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK الممثّلة كقيم عدد صحيح 32-بت.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK المقدمة كقيم صحيحة 32-بت بترتيب بايت KCMY مع قيم قنوات مقلوبة.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | لون ARGB. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// حدد المسار إلى ملفات تعريف RGB و CMYK ICC.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// اقرأ جميع البايتات من ملفات ICC إلى الذاكرة لتتمكن من إعادة ضبط دفق ملف تعريف الإدخال قبل استدعاء toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//المخرجات تبدو هكذا:
//تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC افتراضية.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | int | لون ARGB. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | int | لون ARGB. |

**Returns:**
int - اللون CMYK المقدم كقيمة عدد صحيح 32-بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | لون ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// حدد المسار إلى ملفات تعريف RGB و CMYK ICC.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// اقرأ جميع البايتات من ملفات ICC إلى الذاكرة لتتمكن من إعادة ضبط دفق ملف تعريف الإدخال قبل استدعاء toCmykIcc.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//المخرجات تبدو هكذا:
//تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC افتراضية.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | int | لون ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int - لون CMYK الممثّل كقيمة عدد صحيح 32-بت.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسل | int | لون ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int - ألوان CMYK المقدمة كقيم أعداد صحيحة 32-بت بترتيب بايت KCMY مع قيم القنوات المعكوسة.
