---
title: "ColorTranslator"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "在 GDI Color 结构之间转换颜色。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

在 GDI+ Color 结构之间转换颜色。此类不可被继承。
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | 从 HTML 颜色获取颜色。 |
| [fromOle(int oleColor)](#fromOle-int-) | 从 OLE 颜色获取颜色。 |
| [fromWin32(int win32Color)](#fromWin32-int-) | 从 HTML 颜色获取颜色。 |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | 从颜色创建 HTML 颜色。 |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | 将 OLE 颜色转换为颜色。 |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | 将颜色转换为 Win32 颜色。 |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


从 HTML 颜色获取颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML 颜色。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


从 OLE 颜色获取颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oleColor | int | OLE 颜色。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


从 HTML 颜色获取颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| win32Color | int | Win32 颜色。 |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


从颜色创建 HTML 颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | 颜色类。 |

**Returns:**
java.lang.String - HTML 字符串颜色。
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


将 OLE 颜色转换为颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | 颜色。 |

**Returns:**
int - OLE 颜色。
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


将颜色转换为 Win32 颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | 颜色。 |

**Returns:**
int - Win32 颜色。
