---
title: EmfPlusStringFormat Class
type: docs
weight: 650
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Initializes a new instance of the EmfPlusStringFormat class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets an EmfPlusLanguageIdentifier object that specifies the<br/>            language to use for numeric digits in the string.<br/>            For example, if this string contains Arabic digits,<br/>            this field MUST contain a language identifier that<br/>            specifies an Arabic language |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to substitute<br/>            numeric digits in the string according to a locale or language.<br/>            This value MUST be defined in the StringDigitSubstitution<br/>            enumeration (section 2.1.1.30). |
| first_tab_offset | float | r/w | Gets or sets a 32-bit floating-point value that specifies the number<br/>            of spaces between the beginning of a text line and<br/>            the first tab stop |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Gets or sets a 32-bit signed integer that specifies the type of<br/>            processing that is performed on a string when a keyboard<br/>            shortcut prefix (that is, an ampersand) is encountered.<br/>            Basically, this field specifies whether to display<br/>            keyboard shortcut prefixes that relate to text.<br/>            The value MUST be defined in the HotkeyPrefix<br/>            enumeration (section 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23)<br/>            that specifies the language to use for the string |
| leading_margin | float | r/w | Gets or sets a 32-bit floating-point value that specifies the length<br/>            of the space to add to the starting position of a string.<br/>            The default is 1/6 inch; for typographic fonts, the<br/>            default value is 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to<br/>            align the string vertically in the layout rectangle.<br/>            This value MUST be defined in the StringAlignment enumeration. |
| range_count | int | r/w | Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange<br/>            objects (section 2.2.2.8) defined in the StringFormatData field. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how to<br/>            align the string horizontally in the layout rectangle.<br/>            This value MUST be defined in the StringAlignment<br/>            enumeration (section 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44)<br/>            that specifies optional text layout data. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Gets or sets a 32-bit unsigned integer that specifies text layout<br/>            options for formatting, clipping and font handling.<br/>            This value MUST be composed of StringFormat flags<br/>            (section 2.1.2.8). |
| tabstop_count | int | r/w | Gets or sets a 32-bit signed integer that specifies the number of tab stops<br/>            defined in the StringFormatData field. |
| tracking | float | r/w | Gets or sets a 32-bit floating-point value that specifies the ratio<br/>            of the horizontal space allotted to each character in<br/>            a specified string to the font-defined width of the<br/>            character. Large values for this property specify ample<br/>            space between characters; values less than 1 can produce<br/>            character overlap. The default is 1.03; for typographic<br/>            fonts, the default value is 1.00. |
| trailing_margin | float | r/w | Gets or sets a 32-bit floating-point value that specifies the length<br/>            of the space to leave following a string. The default<br/>            is 1/6 inch; for typographic fonts, the default value is 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Gets or sets specifies how to trim characters from a string that is<br/>            too large to fit into a layout rectangle. This value<br/>            MUST be defined in the StringTrimming enumeration (section 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Gets or sets the version. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Initializes a new instance of the EmfPlusStringFormat class

