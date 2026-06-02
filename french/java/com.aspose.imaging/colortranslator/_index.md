---
title: "ColorTranslator"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Traduit les couleurs vers et depuis les structures GDI Color."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduit les couleurs vers et depuis les structures GDI+ Color. Cette classe ne peut pas être héritée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Prend la couleur du HTML. |
| [fromOle(int oleColor)](#fromOle-int-) | Prend la couleur OLE. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Prend la couleur du HTML. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Crée une couleur HTML à partir de la couleur. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Traduit la couleur OLE en couleur. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Traduit la couleur en couleur win32. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Prend la couleur du HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlColor | java.lang.String | Couleur HTML. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Prend la couleur OLE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oleColor | int | Couleur OLE. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Prend la couleur du HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| win32Color | int | Couleur Win32. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Crée une couleur HTML à partir de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | La classe de couleur. |

**Returns:**
java.lang.String - La couleur de chaîne html.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Traduit la couleur OLE en couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | La couleur. |

**Returns:**
int - La couleur OLE.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Traduit la couleur en couleur win32.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | La couleur. |

**Returns:**
int - La couleur win32.
