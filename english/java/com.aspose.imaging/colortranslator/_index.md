---
title: ColorTranslator
second_title: Aspose.Imaging for Java API Reference
description: Translates colors to and from GDI Color structures.
type: docs
weight: 31
url: /java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Translates colors to and from GDI+ Color structures. This class cannot be inherited.
## Methods

| Method | Description |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Takes color from the HTML color. |
| [fromOle(int oleColor)](#fromOle-int-) | Takes color from the OLE color. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Takes color from the HTML color. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Creates HTML color from the color. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Translates OLE color to color. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Translates the color to win32 color. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Takes color from the HTML color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML color. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Takes color from the OLE color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oleColor | int | OLE color. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Takes color from the HTML color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| win32Color | int | Win32 color. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Creates HTML color from the color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | The color class. |

**Returns:**
java.lang.String - The html string color.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Translates OLE color to color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | The color. |

**Returns:**
int - The OLE color.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Translates the color to win32 color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | The color. |

**Returns:**
int - The win32 color.
