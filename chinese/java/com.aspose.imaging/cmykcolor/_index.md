---
title: "CmykColor"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "像素的 CMYK 颜色。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

像素的 CMYK 颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取空值。 |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | 根据 32 位青色、品红、黄色和黑色值创建一个 `CmykColor` 结构。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 从 32 位 ARGB 颜色转换为 CMYKColor。 |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。 |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB Color。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 从 32 位 ARGB 转换为 CMYKColor。 |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | 从 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | 使用 ICC 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | 使用 ICC 转换将 CMYKColor 转换为 Color。 |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | 获取此 `com.com.aspose.imaging.Color` 结构的青色分量值。 |
| [getM()](#getM--) | 获取此 `com.com.aspose.imaging.Color` 结构的品红分量值。 |
| [getY()](#getY--) | 获取此 `com.com.aspose.imaging.Color` 结构的黄色分量值。 |
| [getK()](#getK--) | 获取此 `com.com.aspose.imaging.Color` 结构的黑色分量值。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `com.com.aspose.imaging.Color` 结构是否未初始化。 |
| [hashCode()](#hashCode--) | 获取哈希码。 |
| [toValue()](#toValue--) | 获取值。 |
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


获取空值。

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


从 32 位青色、品红、黄色和黑色值创建一个 `CmykColor` 结构。此方法已弃用。请使用更有效的 CmykColorHelper\#fromComponents(int, int, int, int)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红 | int | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


从 32 位 ARGB 颜色转换为 CMYKColor。此方法已弃用。请使用更有效的 `CmykColorHelper.toCmyk(int[])`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixels | int[] | 32 位 ARGB 格式的像素。 |

**Returns:**
com.aspose.imaging.CmykColor[] - [CmykColor](../../com.aspose.imaging/cmykcolor) 的数组。
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
com.aspose.imaging.Color[] - ARGB 颜色的数组。
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB Color。此方法已弃用。请使用更有效的 `CmykColorHelper.toArgb32(int[])`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
int[] - 32 位 ARGB 颜色的数组。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


从 32 位 ARGB 转换为 CMYKColor。此方法已弃用。请使用更有效的 `CmykColorHelper.toCmyk(int)`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argbPixel | int | 32 位 ARGB 格式的像素。 |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 `CmykColorHelper.toArgb(int)`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
com.aspose.imaging.Color[] - `com.com.aspose.imaging.Color[]`。
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 `CmykColorHelper.toArgbIcc(int)`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用 ICC 转换将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | java.io.InputStream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
com.aspose.imaging.Color[] - `com.aspose.imaging.Color[]`。
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用 ICC 转换将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 `CmykColorHelper.toArgbIcc(int, Stream, Stream)`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | java.io.InputStream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


获取此 `com.com.aspose.imaging.Color` 结构的青色分量值。

**Returns:**
byte - 此 `com.com.aspose.imaging.Color` 的青色分量值。
### getM() {#getM--}
```
public byte getM()
```


获取此 `com.com.aspose.imaging.Color` 结构的品红分量值。

**Returns:**
byte - 此 `com.com.aspose.imaging.Color` 的品红分量值。
### getY() {#getY--}
```
public byte getY()
```


获取此 `com.com.aspose.imaging.Color` 结构的黄色分量值。

**Returns:**
byte - 此 `com.com.aspose.imaging.Color` 的黄色分量值。
### getK() {#getK--}
```
public byte getK()
```


获取此 `com.com.aspose.imaging.Color` 结构的黑色分量值。

值：此 `com.com.aspose.imaging.Color` 的黑色分量值。

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `com.com.aspose.imaging.Color` 结构是否未初始化。

**Returns:**
boolean - 如果此颜色未初始化，则此属性返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取哈希码。

**Returns:**
int - 该 `int`。
### toValue() {#toValue--}
```
public long toValue()
```


获取值。

**Returns:**
long - 该长 CMYK 值。
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
