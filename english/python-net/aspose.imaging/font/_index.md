---
title: Font Class
type: docs
weight: 4760
url: /python-net/aspose.imaging/font/
---

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Font

**Aspose.Imaging Version:** 23.6

The Font type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Font(prototype, new_style)](#Font_prototype_new_style_0) | Initializes a new instance of the Font class |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initializes a new instance of the Font class |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initializes a new instance of the Font class |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_3) | Initializes a new instance of the Font class |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size, style, unit, and character set. |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_5) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size, style, and unit. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| bold | bool | r | Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is bold. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset) | r | Gets a byte value that specifies the character set that this [Font](/imaging/python-net/aspose.imaging/font/) uses. |
| italic | bool | r | Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is italic. |
| name | string | r | Gets the face name of this [Font](/imaging/python-net/aspose.imaging/font/). |
| strikeout | bool | r | Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) specifies a horizontal line through the font. |
| underline | bool | r | Gets a value indicating whether this [Font](/imaging/python-net/aspose.imaging/font/) is underlined. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) | r | Gets style information for this [Font](/imaging/python-net/aspose.imaging/font/). |
| size | float | r | Gets the em-size of this [Font](/imaging/python-net/aspose.imaging/font/) measured in the units specified by the [unit](/imaging/python-net/aspose.imaging/font/) property. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | r | Gets the unit of measure for this [Font](/imaging/python-net/aspose.imaging/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_prototype(prototype, new_style)](#create_from_prototype_prototype_new_style_6) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) that uses the specified existing [Font](/imaging/python-net/aspose.imaging/font/) and [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumeration. |
| [create_with_size(font_name, em_size)](#create_with_size_font_name_em_size_7) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/), the font style to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [create_with_size_style(font_name, em_size, style)](#create_with_size_style_font_name_em_size_style_8) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and style. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/). |
| [create_with_size_unit(font_name, em_size, unit)](#create_with_size_unit_font_name_em_size_unit_9) | Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and unit. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the style is set to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/). |
| [deep_clone()](#deep_clone__10) | Creates an exact deep copy of this [Font](/imaging/python-net/aspose.imaging/font/). |

### Font(prototype, new_style) {#Font_prototype_new_style_0}


```
 Font(prototype, new_style) 
```

Initializes a new instance of the Font class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) |  |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) |  |

### Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initializes a new instance of the Font class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string |  |
| em_size | float |  |

### Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initializes a new instance of the Font class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string |  |
| em_size | float |  |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) |  |

### Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_3}


```
 Font(font_name, em_size, unit) 
```

Initializes a new instance of the Font class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string |  |
| em_size | float |  |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) |  |

### Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size, style, unit, and character set.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/imaging/python-net/aspose.imaging/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) | The [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) of the new font. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) of the new font. |
| character_set | [CharacterSet](/imaging/python-net/aspose.imaging/characterset) | A character set to use for this font. |

### Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_5}


```
 Font(font_name, em_size, style, unit) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size, style, and unit.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/imaging/python-net/aspose.imaging/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) | The [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) of the new font. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) of the new font. |

### create_from_prototype(prototype, new_style)  [static] {#create_from_prototype_prototype_new_style_6}


```
 create_from_prototype(prototype, new_style) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) that uses the specified existing [Font](/imaging/python-net/aspose.imaging/font/) and [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumeration.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prototype | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | The existing [Font](/imaging/python-net/aspose.imaging/font/) from which to create the new [Font](/imaging/python-net/aspose.imaging/font/). |
| new_style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) | The [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) to apply to the new [Font](/imaging/python-net/aspose.imaging/font/). Multiple values of the [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) enumeration can be combined with the OR operator. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) |  |


### create_with_size(font_name, em_size)  [static] {#create_with_size_font_name_em_size_7}


```
 create_with_size(font_name, em_size) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/), the font style to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/imaging/python-net/aspose.imaging/font/) name. |
| em_size | float | The em-size, in points, of the new font. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) |  |


### create_with_size_style(font_name, em_size, style)  [static] {#create_with_size_style_font_name_em_size_style_8}


```
 create_with_size_style(font_name, em_size, style) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and style. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the graphics unit to [POINT](/imaging/python-net/aspose.imaging/graphicsunit/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/imaging/python-net/aspose.imaging/font/) name. |
| em_size | float | The em-size, in points, of the new font. |
| style | [FontStyle](/imaging/python-net/aspose.imaging/fontstyle) | The [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) of the new font. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) |  |


### create_with_size_unit(font_name, em_size, unit)  [static] {#create_with_size_unit_font_name_em_size_unit_9}


```
 create_with_size_unit(font_name, em_size, unit) 
```

Initializes a new [Font](/imaging/python-net/aspose.imaging/font/) using a specified size and unit. The character set is set to [DEFAULT](/imaging/python-net/aspose.imaging/characterset/), the style is set to [REGULAR](/imaging/python-net/aspose.imaging/fontstyle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/imaging/python-net/aspose.imaging/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) of the new font. |

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) |  |


### deep_clone() {#deep_clone__10}


```
 deep_clone() 
```

Creates an exact deep copy of this [Font](/imaging/python-net/aspose.imaging/font/).

**Returns**

| Type | Description |
| :- | :- |
| [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | The [Font](/imaging/python-net/aspose.imaging/font/) this method creates. |


