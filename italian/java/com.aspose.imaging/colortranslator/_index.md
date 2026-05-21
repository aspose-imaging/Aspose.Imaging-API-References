---
title: "ColorTranslator"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Traduce i colori da e verso le strutture GDI Color."
type: docs
weight: 31
url: /it/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduce i colori da e verso le strutture GDI+ Color. Questa classe non può essere ereditata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Prende il colore dal colore HTML. |
| [fromOle(int oleColor)](#fromOle-int-) | Prende il colore dal colore OLE. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Prende il colore dal colore HTML. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Crea il colore HTML dal colore. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Traduce il colore OLE in colore. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Traduce il colore in colore win32. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Prende il colore dal colore HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlColor | java.lang.String | colore HTML. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Prende il colore dal colore OLE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oleColor | int | colore OLE. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Prende il colore dal colore HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| win32Color | int | colore Win32. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Crea il colore HTML dal colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | La classe colore. |

**Returns:**
java.lang.String - Il colore stringa html.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Traduce il colore OLE in colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Il colore. |

**Returns:**
int - Il colore OLE.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Traduce il colore in colore win32.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Il colore. |

**Returns:**
int - Il colore win32.
