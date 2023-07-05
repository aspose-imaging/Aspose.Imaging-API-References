---
title: EmfPlusStringFormat Class
type: docs
weight: 650
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusStringFormat type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusStringFormat()|Initializes a new instance of the EmfPlusStringFormat class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|version|Gets or sets the version.|
|digit_language|Gets or sets an EmfPlusLanguageIdentifier object that specifies the<br/>            language to use for numeric digits in the string.<br/>            For example, if this string contains Arabic digits,<br/>            this field MUST contain a language identifier that<br/>            specifies an Arabic language|
|digit_substitution|Gets or sets a 32-bit unsigned integer that specifies how to substitute<br/>            numeric digits in the string according to a locale or language.<br/>            This value MUST be defined in the StringDigitSubstitution<br/>            enumeration (section 2.1.1.30).|
|first_tab_offset|Gets or sets a 32-bit floating-point value that specifies the number<br/>            of spaces between the beginning of a text line and<br/>            the first tab stop|
|hotkey_prefix|Gets or sets a 32-bit signed integer that specifies the type of<br/>            processing that is performed on a string when a keyboard<br/>            shortcut prefix (that is, an ampersand) is encountered.<br/>            Basically, this field specifies whether to display<br/>            keyboard shortcut prefixes that relate to text.<br/>            The value MUST be defined in the HotkeyPrefix<br/>            enumeration (section 2.1.1.14).|
|language|Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23)<br/>            that specifies the language to use for the string|
|leading_margin|Gets or sets a 32-bit floating-point value that specifies the length<br/>            of the space to add to the starting position of a string.<br/>            The default is 1/6 inch; for typographic fonts, the<br/>            default value is 0.|
|line_align|Gets or sets a 32-bit unsigned integer that specifies how to<br/>            align the string vertically in the layout rectangle.<br/>            This value MUST be defined in the StringAlignment enumeration.|
|range_count|Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange<br/>            objects (section 2.2.2.8) defined in the StringFormatData field.|
|string_alignment|Gets or sets a 32-bit unsigned integer that specifies how to<br/>            align the string horizontally in the layout rectangle.<br/>            This value MUST be defined in the StringAlignment<br/>            enumeration (section 2.1.1.29).|
|string_format_data|Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44)<br/>            that specifies optional text layout data.|
|string_format_flags|Gets or sets a 32-bit unsigned integer that specifies text layout<br/>            options for formatting, clipping and font handling.<br/>            This value MUST be composed of StringFormat flags<br/>            (section 2.1.2.8).|
|tabstop_count|Gets or sets a 32-bit signed integer that specifies the number of tab stops<br/>            defined in the StringFormatData field.|
|tracking|Gets or sets a 32-bit floating-point value that specifies the ratio<br/>            of the horizontal space allotted to each character in<br/>            a specified string to the font-defined width of the<br/>            character. Large values for this property specify ample<br/>            space between characters; values less than 1 can produce<br/>            character overlap. The default is 1.03; for typographic<br/>            fonts, the default value is 1.00.|
|trailing_margin|Gets or sets a 32-bit floating-point value that specifies the length<br/>            of the space to leave following a string. The default<br/>            is 1/6 inch; for typographic fonts, the default value is 0.|
|trimming|Gets or sets specifies how to trim characters from a string that is<br/>            too large to fit into a layout rectangle. This value<br/>            MUST be defined in the StringTrimming enumeration (section 2.1.1.31).|
