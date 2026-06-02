---
title: "ColorTranslator"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Traduce colores hacia y desde estructuras GDI Color."
type: docs
weight: 31
url: /es/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduce colores hacia y desde estructuras GDI+ Color. Esta clase no puede heredarse.
## Métodos

| Método | Descripción |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Obtiene el color del color HTML. |
| [fromOle(int oleColor)](#fromOle-int-) | Obtiene el color del color OLE. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Obtiene el color del color HTML. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Crea un color HTML a partir del color. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Traduce el color OLE a color. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Traduce el color a color win32. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Obtiene el color del color HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlColor | java.lang.String | Color HTML. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Obtiene el color del color OLE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oleColor | int | Color OLE. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Obtiene el color del color HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| win32Color | int | Color Win32. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Crea un color HTML a partir del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | La clase de color. |

**Returns:**
java.lang.String - El color de cadena html.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Traduce el color OLE a color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | El color. |

**Returns:**
int - El color OLE.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Traduce el color a color win32.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | El color. |

**Returns:**
int - El color win32.
