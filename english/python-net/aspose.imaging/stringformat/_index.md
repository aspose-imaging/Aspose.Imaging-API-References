---
title: StringFormat Class
type: docs
weight: 7310
url: /python-net/aspose.imaging/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [StringFormat(format)](#StringFormat_format_2) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [StringFormat(options)](#StringFormat_options_3) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Gets or sets text alignment information on the vertical plane. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the custom character ident. |
| digit_substitution_language | int | r/w | Gets or sets the language that is used when local digits are substituted for western digits. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | r/w | Gets or sets the method to be used for digit substitution. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| first_tab_offset | float | r | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | r/w | Gets or sets a [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration that contains formatting information. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Gets a generic default [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r | Gets a generic typographic [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | r/w | Gets or sets the [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) object for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | r/w | Gets or sets the line alignment on the horizontal plane. |
| tab_stops | float[] | r | Gets an array of distances between tab stops in the units specified by the [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) property. |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | r/w | Gets or sets the [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) enumeration for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_1) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language. |
| [create_from_format(format)](#create_from_format_format_2) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [deep_clone()](#deep_clone__3) | Creates a deep clone of this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_4) | Sets tab stops for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | The [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from which to initialize the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | The [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration for the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

### Method: create_from_flags(options)  [static] {#create_from_flags_options_1}


```
 create_from_flags(options) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | The [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration for the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: create_from_format(format)  [static] {#create_from_format_format_2}


```
 create_from_format(format) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | The [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from which to initialize the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) |  |


### Method: deep_clone() {#deep_clone__3}


```
 deep_clone() 
```

Creates a deep clone of this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | The deep clone of the current [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_4}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Sets tab stops for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | The number of spaces between the beginning of a line of text and the first tab stop. |
| tab_stops | float[] | An array of distances between tab stops in the units specified by the [Graphics.page_unit](/imaging/python-net/aspose.imaging/graphics/) property. |

