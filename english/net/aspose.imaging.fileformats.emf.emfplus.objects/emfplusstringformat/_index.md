---
title: Class EmfPlusStringFormat
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusStringFormat class. The EmfPlusStringFormat object specifies text layout display manipulations and language identification
type: docs
weight: 5900
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

The EmfPlusStringFormat object specifies text layout, display manipulations, and language identification

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage/) { get; set; } | Gets or sets an EmfPlusLanguageIdentifier object that specifies the language to use for numeric digits in the string. For example, if this string contains Arabic digits, this field MUST contain a language identifier that specifies an Arabic language |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to substitute numeric digits in the string according to a locale or language. This value MUST be defined in the StringDigitSubstitution enumeration (section 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the number of spaces between the beginning of a text line and the first tab stop |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the type of processing that is performed on a string when a keyboard shortcut prefix (that is, an ampersand) is encountered. Basically, this field specifies whether to display keyboard shortcut prefixes that relate to text. The value MUST be defined in the HotkeyPrefix enumeration (section 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language/) { get; set; } | Gets or sets an EmfPlusLanguageIdentifier object (section 2.2.2.23) that specifies the language to use for the string |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the length of the space to add to the starting position of a string. The default is 1/6 inch; for typographic fonts, the default value is 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to align the string vertically in the layout rectangle. This value MUST be defined in the StringAlignment enumeration. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the number of EmfPlusCharacterRange objects (section 2.2.2.8) defined in the StringFormatData field. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to align the string horizontally in the layout rectangle. This value MUST be defined in the StringAlignment enumeration (section 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata/) { get; set; } | Gets or sets an EmfPlusStringFormatData object (section 2.2.2.44) that specifies optional text layout data. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies text layout options for formatting, clipping and font handling. This value MUST be composed of StringFormat flags (section 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the number of tab stops defined in the StringFormatData field. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the ratio of the horizontal space allotted to each character in a specified string to the font-defined width of the character. Large values for this property specify ample space between characters; values less than 1 can produce character overlap. The default is 1.03; for typographic fonts, the default value is 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the length of the space to leave following a string. The default is 1/6 inch; for typographic fonts, the default value is 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming/) { get; set; } | Gets or sets specifies how to trim characters from a string that is too large to fit into a layout rectangle. This value MUST be defined in the StringTrimming enumeration (section 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | Gets or sets the version. |

### See Also

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


