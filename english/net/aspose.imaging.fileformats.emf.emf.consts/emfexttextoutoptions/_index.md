---
title: Enum EmfExtTextOutOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfExtTextOutOptions enum. The ExtTextOutOptions enumeration specifies parameters that control various aspects of the output of text by EMR_SMALLTEXTOUTsection 2.3.5.37 records and in EmrText objects
type: docs
weight: 2720
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
## EmfExtTextOutOptions enumeration

The ExtTextOutOptions enumeration specifies parameters that control various aspects of the output of text by EMR_SMALLTEXTOUT(section 2.3.5.37) records and in EmrText objects.

```csharp
[Flags]
public enum EmfExtTextOutOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ETO_OPAQUE | `2` | This bit indicates that the current background color SHOULD be used to fill the rectangle |
| ETO_CLIPPED | `4` | This bit indicates that the text SHOULD be clipped to the rectangle. |
| ETO_GLYPH_INDEX | `10` | This bit indicates that the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font. Glyph indexes are font-specific, so to display the correct characters on playback, the font that is used MUST be identical to the font used to generate the indexes. |
| ETO_RTLREADING | `80` | This bit indicates that the text MUST be laid out in right-to-left reading order, instead of the default left-to-right order. This SHOULD be applied only when the font selected into the playback device context is either Hebrew or Arabic |
| ETO_NO_RECT | `100` | This bit indicates that the record does not specify a bounding rectangle for the text output. |
| ETO_SMALL_CHARS | `200` | This bit indicates that the codes for characters in an output text string are 8 bits, derived from the low bytes of 16-bit Unicode UTF16-LE character codes, in which the high byte is assumed to be 0. |
| ETO_NUMERICSLOCAL | `400` | This bit indicates that to display numbers, digits appropriate to the locale SHOULD be used |
| ETO_NUMERICSLATIN | `800` | This bit indicates that to display numbers, European digits SHOULD be used |
| ETO_IGNORELANGUAGE | `1000` | This bit indicates that no special operating system processing for glyph placement should be performed on right-to-left strings; that is, all glyph positioning SHOULD be taken care of by drawing and state records in the metafile |
| ETO_PDY | `2000` | This bit indicates that both horizontal and vertical character displacement values SHOULD be provided |
| ETO_REVERSE_INDEX_MAP | `10000` | This bit is reserved and SHOULD NOT be used |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


