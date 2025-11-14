---
title: ColorTranslator Class
type: docs
weight: 1210
url: /python-net/aspose.imaging/colortranslator/
---

**Summary:** Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorTranslator

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_1) | Takes color from the HTML color. |
| [from_ole(ole_color)](#from_ole_ole_color_2) | Takes color from the OLE color. |
| [from_win32(win_32_color)](#from_win32_win_32_color_3) | Takes color from the HTML color. |
| [to_html(c)](#to_html_c_4) | Creates HTML color  from the color. |
| [to_ole(c)](#to_ole_c_5) | Translates OLE color to color. |
| [to_win32(c)](#to_win32_c_6) | Translates the color to win32 color. |


### Method: from_html(html_color)  [static] {#from_html_html_color_1}


```
 from_html(html_color) 
```

Takes color from the HTML color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| html_color | string | HTML color. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The color. |


### Method: from_ole(ole_color)  [static] {#from_ole_ole_color_2}


```
 from_ole(ole_color) 
```

Takes color from the OLE color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| ole_color | int | OLE color. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The color. |


### Method: from_win32(win_32_color)  [static] {#from_win32_win_32_color_3}


```
 from_win32(win_32_color) 
```

Takes color from the HTML color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| win_32_color | int | Win32 color. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The color. |


### Method: to_html(c)  [static] {#to_html_c_4}


```
 to_html(c) 
```

Creates HTML color  from the color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | The color class. |

**Returns**

| Type | Description |
| :- | :- |
| string | The html string color. |


### Method: to_ole(c)  [static] {#to_ole_c_5}


```
 to_ole(c) 
```

Translates OLE color to color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | The color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The OLE color. |


### Method: to_win32(c)  [static] {#to_win32_c_6}


```
 to_win32(c) 
```

Translates the color to win32 color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color/) | The color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The win32 color. |


