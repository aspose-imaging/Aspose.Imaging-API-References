---
title: StringFormat Class
type: docs
weight: 840
url: /python-net/api-reference/aspose.imaging/stringformat/
---

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.StringFormat

**Assembly:**  Aspose.Imaging Version: 23.3.0

The StringFormat type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|StringFormat()|Initializes a new [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|StringFormat(options)|Initializes a new instance of the StringFormat class|
|StringFormat(format)|Initializes a new instance of the StringFormat class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|Gets a value indicating whether this instance is disposed.|
|generic_default|Gets a generic default [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|generic_typographic|Gets a generic typographic [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|format_flags|Gets or sets a [StringFormatFlags](/imaging/python-net/api-reference/aspose.imaging/stringformatflags/) enumeration that contains formatting information.|
|alignment|Gets or sets text alignment information on the vertical plane.|
|line_alignment|Gets or sets the line alignment on the horizontal plane.|
|hotkey_prefix|Gets or sets the [HotkeyPrefix](/imaging/python-net/api-reference/aspose.imaging/hotkeyprefix/) object for this [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|trimming|Gets or sets the [StringTrimming](/imaging/python-net/api-reference/aspose.imaging/stringtrimming/) enumeration for this [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|digit_substitution_method|Gets or sets the method to be used for digit substitution.|
|digit_substitution_language|Gets or sets the language that is used when local digits are substituted for western digits.|
|first_tab_offset|Gets the number of spaces between the beginning of a line of text and the first tab stop.|
|tab_stops|Gets an array of distances between tab stops in the units specified by the [page_unit](/imaging/python-net/api-reference/aspose.imaging/graphics/) property.|
|custom_char_ident|Gets or sets the custom character ident.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_flags(options)|Initializes a new [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object with the specified [StringFormatFlags](/imaging/python-net/api-reference/aspose.imaging/stringformatflags/) enumeration and language.|
|create_from_format(format)|Initializes a new [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object from the specified existing [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|deep_clone()|Creates a deep clone of this [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
|set_tab_stops(first_tab_offset, tab_stops)|Sets tab stops for this [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/) object.|
