---
title: "ColorTranslator"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Übersetzt Farben zu und von GDI‑Color‑Strukturen."
type: docs
weight: 31
url: /de/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Übersetzt Farben zu und von GDI+‑Color‑Strukturen. Diese Klasse kann nicht abgeleitet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Entnimmt die Farbe aus der HTML‑Farbe. |
| [fromOle(int oleColor)](#fromOle-int-) | Entnimmt die Farbe aus der OLE‑Farbe. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Entnimmt die Farbe aus der HTML‑Farbe. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Erstellt eine HTML‑Farbe aus der Farbe. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Übersetzt OLE‑Farbe in Farbe. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Übersetzt die Farbe in Win32‑Farbe. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Entnimmt die Farbe aus der HTML‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML‑Farbe. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Entnimmt die Farbe aus der OLE‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oleColor | int | OLE‑Farbe. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Entnimmt die Farbe aus der HTML‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| win32Color | int | Win32‑Farbe. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Erstellt eine HTML‑Farbe aus der Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Die Farbklasse. |

**Returns:**
java.lang.String - Die HTML‑Stringfarbe.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Übersetzt OLE‑Farbe in Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Die Farbe. |

**Returns:**
int - Die OLE‑Farbe.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Übersetzt die Farbe in Win32‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Die Farbe. |

**Returns:**
int - Die Win32‑Farbe.
