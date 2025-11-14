---
title: EmfExtTextOutOptions Enumeration
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

The ExtTextOutOptions enumeration specifies parameters that control various aspects of the<br/>            output of text by EMR_SMALLTEXTOUT(section 2.3.5.37) records and in EmrText objects.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ETO_CLIPPED | This bit indicates that the text SHOULD be clipped to the rectangle. |
| ETO_GLYPH_INDEX | This bit indicates that the codes for characters in an output text string are actually <br/>            indexes of the character glyphs in a TrueType font. Glyph indexes are font-specific, <br/>            so to display the correct characters on playback, the font that is used MUST be <br/>            identical to the font used to generate the indexes. |
| ETO_IGNORELANGUAGE | This bit indicates that no special operating system processing for glyph placement should be <br/>            performed on right-to-left strings; that is, all glyph positioning SHOULD be taken care of by <br/>            drawing and state records in the metafile |
| ETO_NO_RECT | This bit indicates that the record does not specify a bounding rectangle for the text output. |
| ETO_NUMERICSLATIN | This bit indicates that to display numbers, European digits SHOULD be used |
| ETO_NUMERICSLOCAL | This bit indicates that to display numbers, digits appropriate to the locale SHOULD be used |
| ETO_OPAQUE | This bit indicates that the current background color SHOULD be used to fill the rectangle |
| ETO_PDY | This bit indicates that both horizontal and vertical character displacement values SHOULD be provided |
| ETO_REVERSE_INDEX_MAP | This bit is reserved and SHOULD NOT be used |
| ETO_RTLREADING | This bit indicates that the text MUST be laid out in right-to-left reading order, <br/>            instead of the default left-to-right order. This SHOULD be applied only when the font<br/>            selected into the playback device context is either Hebrew or Arabic |
| ETO_SMALL_CHARS | This bit indicates that the codes for characters in an output text string are 8 bits, <br/>            derived from the low bytes of 16-bit Unicode UTF16-LE character codes, <br/>            in which the high byte is assumed to be 0. |
