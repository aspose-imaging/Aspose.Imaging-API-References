---
title: "ColorTranslator"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يترجم الألوان إلى ومن هياكل لون GDI."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

يترجم الألوان إلى ومن هياكل لون GDI+. لا يمكن وراثة هذه الفئة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | يأخذ اللون من لون HTML. |
| [fromOle(int oleColor)](#fromOle-int-) | يأخذ اللون من لون OLE. |
| [fromWin32(int win32Color)](#fromWin32-int-) | يأخذ اللون من لون HTML. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | ينشئ لون HTML من اللون. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | يترجم لون OLE إلى اللون. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | يترجم اللون إلى لون win32. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


يأخذ اللون من لون HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlColor | java.lang.String | لون HTML. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


يأخذ اللون من لون OLE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oleColor | int | لون OLE. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


يأخذ اللون من لون HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| win32Color | int | لون Win32. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


ينشئ لون HTML من اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | فئة اللون. |

**Returns:**
java.lang.String - لون سلسلة HTML.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


يترجم لون OLE إلى اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | اللون. |

**Returns:**
int - لون OLE.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


يترجم اللون إلى لون win32.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | اللون. |

**Returns:**
int - لون win32.
