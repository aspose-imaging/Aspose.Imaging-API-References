---
title: "ColorTranslator 类"
type: docs
weight: 1210
url: /zh/python-net/aspose.imaging/colortranslator/
---

**Summary:** Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorTranslator

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_1) | 从 HTML 颜色获取颜色。 |
| [from_ole(ole_color)](#from_ole_ole_color_2) | 从 OLE 颜色获取颜色。 |
| [from_win32(win_32_color)](#from_win32_win_32_color_3) | 从 HTML 颜色获取颜色。 |
| [to_html(c)](#to_html_c_4) | 从颜色创建 HTML 颜色。 |
| [to_ole(c)](#to_ole_c_5) | 将 OLE 颜色转换为颜色。 |
| [to_win32(c)](#to_win32_c_6) | 将颜色转换为 win32 颜色。 |


### Method: from_html(html_color)  [static] {#from_html_html_color_1}


```
 from_html(html_color) 
```

从 HTML 颜色获取颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| html_color | string | HTML 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该颜色。 |


### Method: from_ole(ole_color)  [static] {#from_ole_ole_color_2}


```
 from_ole(ole_color) 
```

从 OLE 颜色获取颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ole_color | int | OLE 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该颜色。 |


### Method: from_win32(win_32_color)  [static] {#from_win32_win_32_color_3}


```
 from_win32(win_32_color) 
```

从 HTML 颜色获取颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| win_32_color | int | Win32 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 该颜色。 |


### Method: to_html(c)  [static] {#to_html_c_4}


```
 to_html(c) 
```

从颜色创建 HTML 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色类。 |

**Returns**

| Type | Description |
| :- | :- |
| string | HTML 字符串颜色。 |


### Method: to_ole(c)  [static] {#to_ole_c_5}


```
 to_ole(c) 
```

将 OLE 颜色转换为颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | 该颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | OLE 颜色。 |


### Method: to_win32(c)  [static] {#to_win32_c_6}


```
 to_win32(c) 
```

将颜色转换为 win32 颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | 该颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | Win32 颜色。 |


