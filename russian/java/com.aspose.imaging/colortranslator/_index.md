---
title: "ColorTranslator"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Преобразует цвета в структуры GDI Color и из них."
type: docs
weight: 31
url: /ru/java/com.aspose.imaging/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Преобразует цвета в структуры GDI+ Color и из них. Этот класс нельзя наследовать.
## Методы

| Метод | Описание |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Берёт цвет из HTML‑цвета. |
| [fromOle(int oleColor)](#fromOle-int-) | Берёт цвет из OLE‑цвета. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Берёт цвет из HTML‑цвета. |
| [toHtml(Color c)](#toHtml-com.aspose.imaging.Color-) | Создаёт HTML‑цвет из цвета. |
| [toOle(Color c)](#toOle-com.aspose.imaging.Color-) | Преобразует OLE‑цвет в цвет. |
| [toWin32(Color c)](#toWin32-com.aspose.imaging.Color-) | Преобразует цвет в win32‑цвет. |
### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Берёт цвет из HTML‑цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlColor | java.lang.String | HTML‑цвет. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Берёт цвет из OLE‑цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oleColor | int | OLE‑цвет. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Берёт цвет из HTML‑цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| win32Color | int | Win32‑цвет. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color.
### toHtml(Color c) {#toHtml-com.aspose.imaging.Color-}
```
public static String toHtml(Color c)
```


Создаёт HTML‑цвет из цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Класс цвета. |

**Returns:**
java.lang.String — HTML‑строка цвета.
### toOle(Color c) {#toOle-com.aspose.imaging.Color-}
```
public static int toOle(Color c)
```


Преобразует OLE‑цвет в цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Цвет. |

**Returns:**
int — OLE‑цвет.
### toWin32(Color c) {#toWin32-com.aspose.imaging.Color-}
```
public static int toWin32(Color c)
```


Преобразует цвет в win32‑цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.imaging/color) | Цвет. |

**Returns:**
int — Win32‑цвет.
