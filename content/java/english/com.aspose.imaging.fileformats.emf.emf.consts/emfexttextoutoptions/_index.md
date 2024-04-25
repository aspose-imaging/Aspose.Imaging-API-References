---
title: EmfExtTextOutOptions
second_title: Aspose.Imaging for Java API Reference
description: The ExtTextOutOptions enumeration specifies parameters that control various aspects of the output of text by EMR_SMALLTEXTOUTsection 2.3.5.37 records and in EmrText objects.
type: docs
weight: 19
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

The ExtTextOutOptions enumeration specifies parameters that control various aspects of the output of text by EMR\_SMALLTEXTOUT(section 2.3.5.37) records and in EmrText objects.
## Fields

| Field | Description |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | This bit indicates that the current background color SHOULD be used to fill the rectangle |
| [ETO_CLIPPED](#ETO-CLIPPED) | This bit indicates that the text SHOULD be clipped to the rectangle. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | This bit indicates that the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font. |
| [ETO_RTLREADING](#ETO-RTLREADING) | This bit indicates that the text MUST be laid out in right-to-left reading order, instead of the default left-to-right order. |
| [ETO_NO_RECT](#ETO-NO-RECT) | This bit indicates that the record does not specify a bounding rectangle for the text output. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | This bit indicates that the codes for characters in an output text string are 8 bits, derived from the low bytes of 16-bit Unicode UTF16-LE character codes, in which the high byte is assumed to be 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | This bit indicates that to display numbers, digits appropriate to the locale SHOULD be used |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | This bit indicates that to display numbers, European digits SHOULD be used |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | This bit indicates that no special operating system processing for glyph placement should be performed on right-to-left strings; that is, all glyph positioning SHOULD be taken care of by drawing and state records in the metafile |
| [ETO_PDY](#ETO-PDY) | This bit indicates that both horizontal and vertical character displacement values SHOULD be provided |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | This bit is reserved and SHOULD NOT be used |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


This bit indicates that the current background color SHOULD be used to fill the rectangle

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


This bit indicates that the text SHOULD be clipped to the rectangle.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


This bit indicates that the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font. Glyph indexes are font-specific, so to display the correct characters on playback, the font that is used MUST be identical to the font used to generate the indexes.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


This bit indicates that the text MUST be laid out in right-to-left reading order, instead of the default left-to-right order. This SHOULD be applied only when the font selected into the playback device context is either Hebrew or Arabic

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


This bit indicates that the record does not specify a bounding rectangle for the text output.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


This bit indicates that the codes for characters in an output text string are 8 bits, derived from the low bytes of 16-bit Unicode UTF16-LE character codes, in which the high byte is assumed to be 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


This bit indicates that to display numbers, digits appropriate to the locale SHOULD be used

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


This bit indicates that to display numbers, European digits SHOULD be used

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


This bit indicates that no special operating system processing for glyph placement should be performed on right-to-left strings; that is, all glyph positioning SHOULD be taken care of by drawing and state records in the metafile

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


This bit indicates that both horizontal and vertical character displacement values SHOULD be provided

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


This bit is reserved and SHOULD NOT be used

