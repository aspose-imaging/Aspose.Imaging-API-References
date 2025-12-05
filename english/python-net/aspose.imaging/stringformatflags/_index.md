---
title: StringFormatFlags Enumeration
type: docs
weight: 11150
url: /python-net/aspose.imaging/stringformatflags/
---

Specifies the display and layout information for text strings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Text is displayed from right to left. |
| DIRECTION_VERTICAL | Text is vertically aligned. |
| DISPLAY_FORMAT_CONTROL | Control characters such as the left-to-right mark are shown in the output with a representative glyph. |
| EXACT_ALIGNMENT | The exact alignment, correct padding GDI+ |
| FIT_BLACK_BOX | Parts of characters are allowed to overhang the string's layout rectangle. By default, characters are repositioned to avoid any overhang. |
| LINE_LIMIT | Only entire lines are laid out in the formatting rectangle. By default layout continues until the end of the text, or until no more lines are visible as a result of clipping, whichever comes first.<br/>            Note that the default settings allow the last line to be partially obscured by a formatting rectangle that is not a whole multiple of the line height. To ensure that only whole lines are seen,<br/>            specify this value and be careful to provide a formatting rectangle at least as tall as the height of one line. |
| MEASURE_TRAILING_SPACES | Includes the trailing space at the end of each line. By default the boundary rectangle returned by the MeasureString method excludes the space at the end of each line. Set this flag to include that space in measurement. |
| NO_CLIP | Overhanging parts of glyphs, and unwrapped text reaching outside the formatting rectangle are allowed to show. By default all text and glyph parts reaching outside the formatting rectangle are clipped. |
| NO_FONT_FALLBACK | Fallback to alternate fonts for characters not supported in the requested font is disabled. Any missing characters are displayed with the fonts missing glyph, usually an open square. |
| NO_WRAP | Text wrapping between lines when formatting within a rectangle is disabled. This flag is implied when a point is passed instead of a rectangle, or when the specified rectangle has a zero line length. |
