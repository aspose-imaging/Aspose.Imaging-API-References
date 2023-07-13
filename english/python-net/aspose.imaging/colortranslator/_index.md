---
title: ColorTranslator Class
type: docs
weight: 1200
url: /python-net/aspose.imaging/colortranslator/
---

Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorTranslator

**Aspose.Imaging Version:** 23.6

The ColorTranslator type exposes the following members:
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_0) | Takes color from the HTML color. |
| [from_ole(ole_color)](#from_ole_ole_color_1) | Takes color from the OLE color. |
| [from_win32(win_32_color)](#from_win32_win_32_color_2) | Takes color from the HTML color. |
| [to_html(c)](#to_html_c_3) | Creates HTML color  from the color. |
| [to_ole(c)](#to_ole_c_4) | Translates OLE color to color. |
| [to_win32(c)](#to_win32_c_5) | Translates the color to win32 color. |

### from_html(html_color)  [static] {#from_html_html_color_0}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The color. |


### from_ole(ole_color)  [static] {#from_ole_ole_color_1}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The color. |


### from_win32(win_32_color)  [static] {#from_win32_win_32_color_2}


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
| [Color](/imaging/python-net/aspose.imaging/color) | The color. |


### to_html(c)  [static] {#to_html_c_3}


```
 to_html(c) 
```

Creates HTML color  from the color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color) | The color class. |

**Returns**

| Type | Description |
| :- | :- |
| string | The html string color. |


### to_ole(c)  [static] {#to_ole_c_4}


```
 to_ole(c) 
```

Translates OLE color to color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color) | The color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The OLE color. |


### to_win32(c)  [static] {#to_win32_c_5}


```
 to_win32(c) 
```

Translates the color to win32 color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Color](/imaging/python-net/aspose.imaging/color) | The color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The win32 color. |


