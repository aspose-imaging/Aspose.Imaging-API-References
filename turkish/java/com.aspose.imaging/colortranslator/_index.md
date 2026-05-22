---
title: "ColorTranslator"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Renkleri GDI Color yapılarıyla ileri ve geri çevirir."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Renkleri GDI+ Color yapılarıyla ileri ve geri çevirir. Bu sınıf miras alınamaz.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Rengi HTML renginden alır. |
| [fromOle(int oleColor)](#fromOle-int-) | Rengi OLE renginden alır. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Rengi HTML renginden alır. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Renkten HTML rengi oluşturur. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | OLE rengini renge çevirir. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Rengi win32 rengine çevirir. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Rengi HTML renginden alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML rengi. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Rengi OLE renginden alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oleColor | int | OLE rengi. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Rengi HTML renginden alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| win32Color | int | Win32 rengi. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Renkten HTML rengi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Renk sınıfı. |

**Returns:**
java.lang.String - HTML dize rengi.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


OLE rengini renge çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Renk. |

**Returns:**
int - OLE rengi.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Rengi win32 rengine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Renk. |

**Returns:**
int - win32 rengi.
