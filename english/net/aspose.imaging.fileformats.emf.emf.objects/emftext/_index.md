---
title: Class EmfText
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfText class. The EmrText object contains values for text output
type: docs
weight: 3250
url: /net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---
## EmfText class

The EmrText object contains values for text output.

```csharp
public sealed class EmfText : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfText](emftext/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Chars](../../aspose.imaging.fileformats.emf.emf.objects/emftext/chars/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string |
| [DxBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/) { get; set; } | Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined, this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO_PDY flag, then this buffer contains twice as many values as there are characters in the output string, one horizontal and one vertical offset for each, in that order. If ETO_RTLREADING is specified, characters are laid right to left instead of left to right. No other options affect the interpretation of this field. |
| [GlyphIndexBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/glyphindexbuffer/) { get; set; } | Gets or sets the optional glyph index buffer. If options has ETO_GLYPH_INDEX flag then the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font (2.1.11 ExtTextOutOptions enumeration). Glyph indexes are font-specific, so to display the correct characters on playback, the font that is used MUST be identical to the font used to generate the indexes. |
| [Options](../../aspose.imaging.fileformats.emf.emf.objects/emftext/options/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. This field can be a combination of more than one ExtTextOutOptions enumeration (section 2.1.11) values |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.objects/emftext/rectangle/) { get; set; } | Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. This rectangle is applied to the text output performed by the containing record. |
| [Reference](../../aspose.imaging.fileformats.emf.emf.objects/emftext/reference/) { get; set; } | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. The reference point is defined by the last EMR_SETTEXTALIGN record (section 2.3.11.25). If no such record has been set, the default alignment is TA_LEFT,TA_TOP. |
| [StringBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/stringbuffer/) { get; set; } | Gets or sets the character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. The OutputString field is not required to follow immediately the preceding portion of this structure. OutputString (variable): An array of characters that specify the string to output. The location of this field is specified by the value of offString in bytes from the start of this record. The number of characters is specified by the value of Chars. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


