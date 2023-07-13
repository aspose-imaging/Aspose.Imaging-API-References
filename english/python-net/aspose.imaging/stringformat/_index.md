---
title: StringFormat Class
type: docs
weight: 7160
url: /python-net/aspose.imaging/stringformat/
---

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormat

**Inheritance:** DisposableObject

**Aspose.Imaging Version:** 23.6

The StringFormat type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [StringFormat()](#StringFormat__0) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [StringFormat(options)](#StringFormat_options_1) | Initializes a new instance of the StringFormat class |
| [StringFormat(format)](#StringFormat_format_2) | Initializes a new instance of the StringFormat class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| generic_default [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | r | Gets a generic default [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| generic_typographic [static] | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | r | Gets a generic typographic [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| format_flags | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags) | r/w | Gets or sets a [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration that contains formatting information. |
| alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment) | r/w | Gets or sets text alignment information on the vertical plane. |
| line_alignment | [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment) | r/w | Gets or sets the line alignment on the horizontal plane. |
| hotkey_prefix | [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix) | r/w | Gets or sets the [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) object for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| trimming | [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming) | r/w | Gets or sets the [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) enumeration for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| digit_substitution_method | [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute) | r/w | Gets or sets the method to be used for digit substitution. |
| digit_substitution_language | int | r/w | Gets or sets the language that is used when local digits are substituted for western digits. |
| first_tab_offset | float | r | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| tab_stops | float | r | Gets an array of distances between tab stops in the units specified by the [page_unit](/imaging/python-net/aspose.imaging/graphics/) property. |
| custom_char_ident | [PointF](/imaging/python-net/aspose.imaging/pointf) | r/w | Gets or sets the custom character ident. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_flags(options)](#create_from_flags_options_3) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language. |
| [create_from_format(format)](#create_from_format_format_4) | Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [deep_clone()](#deep_clone__5) | Creates a deep clone of this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_6) | Sets tab stops for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

### StringFormat() {#StringFormat__0}


```
 StringFormat() 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

### StringFormat(options) {#StringFormat_options_1}


```
 StringFormat(options) 
```

Initializes a new instance of the StringFormat class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags) |  |

### StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initializes a new instance of the StringFormat class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) |  |

### create_from_flags(options)  [static] {#create_from_flags_options_3}


```
 create_from_flags(options) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration and language.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags) | The [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) enumeration for the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat) |  |


### create_from_format(format)  [static] {#create_from_format_format_4}


```
 create_from_format(format) 
```

Initializes a new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | The [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object from which to initialize the new [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat) |  |


### deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Creates a deep clone of this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | The deep clone of the current [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |


### set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_6}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Sets tab stops for this [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | The number of spaces between the beginning of a line of text and the first tab stop. |
| tab_stops | float | An array of distances between tab stops in the units specified by the [page_unit](/imaging/python-net/aspose.imaging/graphics/) property. |

