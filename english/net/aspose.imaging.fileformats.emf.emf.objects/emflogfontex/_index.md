---
title: Class EmfLogFontEx
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogFontEx class. The LogFontEx object specifies the extended attributes of a logical font
type: docs
weight: 3130
url: /net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---
## EmfLogFontEx class

The LogFontEx object specifies the extended attributes of a logical font.

```csharp
public class EmfLogFontEx : EmfLogFont
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfLogFontEx](emflogfontex/)(EmfLogFont) | Initializes a new instance of the `EmfLogFontEx` class. |

## Properties

| Name | Description |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. It MUST be a value in the WMF CharacterSet enumeration ([MS-WMF] section 2.1.1.5). If the character set is unknown, metafile processing SHOULD NOT attempt to translate or interpret strings that are rendered with that font. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the clipping precision. The clipping precision defines how to clip characters that are partially outside the clipping region. It can be one or more of the WMF ClipPrecision Flags |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. The escapement vector is parallel to the baseline of a row of text. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename/) { get; set; } | Gets or sets a Facename (64 bytes): A string of no more than 32 Unicode characters that specifies the typeface name of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/fullname/) { get; set; } | Gets or sets a string of 64 Unicode characters that contains the font's full name. If the length of this string is less than 64 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. The character height value, also known as the em size, is the character cell height value minus the internal leading value. The font mapper SHOULD interpret the value specified in the Height field in the following manner. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the output precision. The output precision defines how closely the font is required to match the requested height, width, character orientation, escapement, pitch, and font type. It MUST be a value from the WMF OutPrecision enumeration |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily/) { get; set; } | Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. Font families describe the look of a font in a general way. They are intended for specifying a font when the specified typeface is not available. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the output quality. The output quality defines how closely to attempt to match the logical-font attributes to those of an actual physical font. It MUST be one of the values in the WMF FontQuality enumeration ([MS-WMF] section 2.1.1.10). |
| [Script](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/script/) { get; set; } | Gets or sets a string of 32 Unicode characters that defines the character set of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored. |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/style/) { get; set; } | Gets or sets a string of 32 Unicode characters that defines the font's style. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the weight of the font in the range zero through 1000. For example, 400 is normal and 700 is bold. If this value is zero, a default weight can be used. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of characters in the font. If the Width field value is zero, an appropriate value SHOULD be calculated from other LogFont values to find a font that has the typographer's intended aspect ratio |

### See Also

* class [EmfLogFont](../emflogfont/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


