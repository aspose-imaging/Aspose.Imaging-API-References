---
title: Enum StringFormatFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.StringFormatFlags enum. Specifies the display and layout information for text strings
type: docs
weight: 11670
url: /net/aspose.imaging/stringformatflags/
---
## StringFormatFlags enumeration

Specifies the display and layout information for text strings.

```csharp
[Flags]
public enum StringFormatFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Text is displayed from right to left. |
| DirectionVertical | `2` | Text is vertically aligned. |
| FitBlackBox | `4` | Parts of characters are allowed to overhang the string's layout rectangle. By default, characters are repositioned to avoid any overhang. |
| DisplayFormatControl | `20` | Control characters such as the left-to-right mark are shown in the output with a representative glyph. |
| NoFontFallback | `400` | Fallback to alternate fonts for characters not supported in the requested font is disabled. Any missing characters are displayed with the fonts missing glyph, usually an open square. |
| MeasureTrailingSpaces | `800` | Includes the trailing space at the end of each line. By default the boundary rectangle returned by the MeasureString method excludes the space at the end of each line. Set this flag to include that space in measurement. |
| NoWrap | `1000` | Text wrapping between lines when formatting within a rectangle is disabled. This flag is implied when a point is passed instead of a rectangle, or when the specified rectangle has a zero line length. |
| LineLimit | `2000` | Only entire lines are laid out in the formatting rectangle. By default layout continues until the end of the text, or until no more lines are visible as a result of clipping, whichever comes first. Note that the default settings allow the last line to be partially obscured by a formatting rectangle that is not a whole multiple of the line height. To ensure that only whole lines are seen, specify this value and be careful to provide a formatting rectangle at least as tall as the height of one line. |
| NoClip | `4000` | Overhanging parts of glyphs, and unwrapped text reaching outside the formatting rectangle are allowed to show. By default all text and glyph parts reaching outside the formatting rectangle are clipped. |
| ExactAlignment | `8000` | The exact alignment, correct padding GDI+ |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


