---
title: EmfPlusStringFormatFlags Enumeration
type: docs
weight: 410
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

The StringFormat flags specify options for graphics text layout, including direction, clipping and font handling. These flags can be combined to specify multiple options.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | This flag MAY be used to specify an implementation-specific process for rendering text. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | If set, the reading order of the string SHOULD be right to left. For horizontal text, this means that characters are read from right to left. For vertical text, this means that columns are read from right to left.<br/>            If clear, horizontal or vertical text SHOULD be read from left to right. |
| STRING_FORMAT_DIRECTION_VERTICAL | If set, individual lines of text SHOULD be drawn vertically on the display device.<br/>            If clear, individual lines of text SHOULD be drawn horizontally, with each new line below the previous line. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | If set, control characters SHOULD appear in the output as representative Unicode glyphs. |
| STRING_FORMAT_LINE_LIMIT | If set, whole lines of text SHOULD be output and SHOULD NOT be clipped by the string's layout rectangle.<br/>            If clear, text layout SHOULD continue until all lines are output, or until additional lines would not be visible as a result of clipping.<br/>            This flag can be used either to deny or allow a line of text to be partially obscured by a layout rectangle that is not a multiple of line height. For all text to be visible, a layout rectangle at least as tall as the height of one line. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | If set, the space at the end of each line MUST be included in measurements of string length.<br/>            If clear, the space at the end of each line MUST be excluded from measurements of string length. |
| STRING_FORMAT_NO_CLIP | If set, text extending outside the string layout rectangle SHOULD be allowed to show.<br/>            If clear, all text that extends outside the layout rectangle SHOULD be clipped. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | If set, parts of characters MUST be allowed to overhang the text layout rectangle.<br/>            If clear, characters that overhang the boundaries of the text layout rectangle MUST be repositioned to avoid overhang.<br/>            An italic, "f" is an example of a character that can have overhanging parts. |
| STRING_FORMAT_NO_FONT_FALLBACK | If set, an alternate font SHOULD be used for characters that are not supported in the requested font.<br/>            If clear, a character missing from the requested font SHOULD appear as a "font missing" character, which MAY be an open square. |
| STRING_FORMAT_NO_WRAP | If set, a string that extends past the end of the text layout rectangle MUST NOT be wrapped to the next line.<br/>            If clear, a string that extends past the end of the text layout rectangle MUST be broken at the last word boundary within the bounding rectangle, and the remainder of the string MUST be wrapped to the next line. |
