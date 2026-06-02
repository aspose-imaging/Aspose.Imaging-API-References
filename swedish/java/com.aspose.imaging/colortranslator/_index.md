---
title: "ColorTranslator"
second_title: "Aspose.Imaging för Java API-referens"
description: "Översätter färger till och från GDI Color-strukturer."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Översätter färger till och från GDI+ Color-strukturer. Denna klass kan inte ärvas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Hämtar färg från HTML-färgen. |
| [fromOle(int oleColor)](#fromOle-int-) | Hämtar färg från OLE-färgen. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Hämtar färg från HTML-färgen. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Skapar HTML-färg från färgen. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Översätter OLE-färg till färg. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Översätter färgen till win32-färg. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Hämtar färg från HTML-färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML-färg. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Hämtar färg från OLE-färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oleColor | int | OLE-färg. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Hämtar färg från HTML-färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| win32Color | int | Win32-färg. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Skapar HTML-färg från färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Färgklassen. |

**Returns:**
java.lang.String - HTML-strängfärgen.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Översätter OLE-färg till färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Färgen. |

**Returns:**
int - OLE-färgen.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Översätter färgen till win32-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Färgen. |

**Returns:**
int - win32-färgen.
