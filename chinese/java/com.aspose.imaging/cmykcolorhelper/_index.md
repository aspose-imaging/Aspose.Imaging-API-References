---
title: "CmykColorHelper"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于处理以有符号 32 位整数表示的 CMYK 颜色的辅助方法。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

帮助方法用于处理以有符号 32 位整数值表示的 CMYK 颜色。提供与 [CmykColor](../../com.aspose.imaging/cmykcolor) 结构体相似的 API。由于 CMYK 颜色仅以 Int32 而非包含内部字段的结构体表示，它更轻量。请在可能的情况下优先使用此类的静态方法，而不是已弃用的 [CmykColor](../../com.aspose.imaging/cmykcolor) 结构体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | 获取青色分量值。 |
| [getM(int cmyk)](#getM-int-) | 获取品红分量值。 |
| [getY(int cmyk)](#getY-int-) | 获取黄色分量值。 |
| [getK(int cmyk)](#getK-int-) | 获取黑色分量值。 |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 从 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | 将 ARGB 转换为 CMYK。 |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | 将 ARGB 转换为 CMYKA（带透明度）。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgb(int cmykPixel)](#toArgb-int-) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | 执行从 CMYK 颜色到 ARGB 颜色的转换，如果 `reuseArray` 为 true，则将结果存储到同一数组中。 |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。 |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。 |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。 |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


获取青色分量值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmyk | int | CMYK 颜色以 32 位整数值表示。 |

**Returns:**
int - 青色分量值。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


获取品红分量值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmyk | int | CMYK 颜色以 32 位整数值表示。 |

**Returns:**
int - 品红分量值。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


获取黄色分量值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmyk | int | CMYK 颜色以 32 位整数值表示。 |

**Returns:**
int - 黄色分量值。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


获取黑色分量值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmyk | int | CMYK 颜色以 32 位整数值表示。 |

**Returns:**
int - 黑色分量值。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


从 32 位青色、品红、黄色和黑色值创建 CMYK。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红 | int | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


从 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixels | int[] | ARGB 颜色以 32 位整数表示。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


将 ARGB 转换为 CMYK。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixels | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


将 ARGB 转换为 CMYKA（带透明度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixels | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


从 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixel | int | 以 32 位整数值形式呈现的 ARGB 颜色。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


从 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB 颜色。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


从 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB 颜色。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


从 CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值形式呈现的 CMYK 颜色。 |

**Returns:**
com.aspose.imaging.Color[] - ARGB 颜色。
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


从 CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | int | CMYK 颜色以 32 位整数值表示。 |

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

//输出如下：
//在不使用 ICC 配置文件的情况下将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


从 CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值形式呈现的 CMYK 颜色。 |

**Returns:**
int[] - 以 32 位整数值形式呈现的 ARGB 颜色。
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


如果 `reuseArray` 为 true，则执行将 CMYK 颜色转换为 ARGB 颜色的操作，并将结果存储到同一数组中。否则，将分配新的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值形式呈现的 CMYK 颜色。 |
| reuseArray | boolean | 如果 `true`，输入的 `cmykPixels` 数组将被新值重新填充并返回；否则将分配并返回一个新数组。 |

**Returns:**
int[] - 新分配的数组或已填充 ARGB 颜色（以 32 位整数值形式呈现）的 `cmykPixels`。
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值形式呈现的 CMYK 像素。 |

**Returns:**
com.aspose.imaging.Color[] - ARGB 颜色。
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值形式呈现的 CMYK 颜色。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |

**Returns:**
com.aspose.imaging.Color[] - ARGB 颜色。
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | int | CMYK 颜色以 32 位整数值表示。 |

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

// 指定自定义 RGB 和 CMYK ICC 配置文件的路径。
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// 将 ICC 文件的所有字节读取到内存，以便在调用 toCmykIcc 之前能够重置输入配置文件流。
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

//输出如下：
//使用默认 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | int | CMYK 颜色以 32 位整数值表示。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |

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

// 指定自定义 RGB 和 CMYK ICC 配置文件的路径。
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// 将 ICC 文件的所有字节读取到内存，以便在调用 toCmykIcc 之前能够重置输入配置文件流。
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

//输出如下：
//使用默认 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//使用自定义 ICC 配置文件将 CMYK 转换为 RGB。
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| rgbIccStream | java.io.InputStream | RGB 配置文件流。 |
| cmykIccStream | java.io.InputStream | CMYK 配置文件流。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| cmykBytes | byte[] | Cmyk 字节。 |
| cmykOffset | int | `cmykBytes` 偏移量。 |
| rgbIccStream | java.io.InputStream | RGB 配置文件流。 |
| cmykIccStream | java.io.InputStream | CMYK 配置文件流。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| cmykBytes | byte[] | Cmyk 字节。 |
| cmykOffset | int | `cmykBytes` 偏移量。 |
| rgbIccStream | java.io.InputStream | RGB 配置文件流。 |
| cmykIccStream | java.io.InputStream | CMYK 配置文件流。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件通过 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。采用 PSD CMYK 格式的 KCMY 字节顺序，并使用反转的通道值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int[] - 以 KCMY 字节顺序的 32 位整数值表示的 CMYK 颜色，通道值已反转。
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义 ICC 配置文件将 RGB 转换为 CMYKA（带 alpha）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | RGB 颜色以 32 位整数表示。 |
| startIndex | int | RGB 颜色的起始索引。 |
| length | int | 要转换的 RGB 像素数量。 |
| rgbIccStream | java.io.InputStream | RGB 配置文件流。 |
| cmykIccStream | java.io.InputStream | CMYK 配置文件流。 |

**Returns:**
byte[] - 以字节数组形式呈现的 CMYK 颜色。
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB 颜色。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | ARGB 颜色。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数表示。
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


使用默认配置文件通过 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。采用 PSD CMYK 格式的 KCMY 字节顺序，并使用反转的通道值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | ARGB 颜色。 |

**Returns:**
int[] - 以 KCMY 字节顺序的 32 位整数值表示的 CMYK 颜色，通道值已反转。
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB 颜色。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。

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

// 指定 RGB 和 CMYK ICC 配置文件的路径。
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// 将 ICC 文件的所有字节读取到内存，以便在调用 toCmykIcc 之前能够重置输入配置文件流。
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

//输出如下：
//使用默认 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | int | ARGB 颜色。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


使用默认配置文件通过 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。采用 PSD CMYK 格式的 KCMY 字节顺序，并使用反转的通道值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | int | ARGB 颜色。 |

**Returns:**
int - 以 KCMY 字节顺序呈现的 CMYK 颜色，使用反转的通道值，作为 32 位整数值。
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。

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

// 指定 RGB 和 CMYK ICC 配置文件的路径。
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// 将 ICC 文件的所有字节读取到内存，以便在调用 toCmykIcc 之前能够重置输入配置文件流。
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

//输出如下：
//使用默认 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//使用自定义 ICC 配置文件将 RGB 转换为 CMYK。
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | int | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int - 以 32 位整数表示的 CMYK 颜色。
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int - 以 KCMY 字节顺序呈现的 CMYK 颜色，使用反转的通道值，作为 32 位整数值。
