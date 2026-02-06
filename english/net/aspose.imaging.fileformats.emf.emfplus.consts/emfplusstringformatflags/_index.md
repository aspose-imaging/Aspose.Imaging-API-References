---
title: Enum EmfPlusStringFormatFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusStringFormatFlags enum. The StringFormat flags specify options for graphics text layout including direction clipping and font handling. These flags can be combined to specify multiple options
type: docs
weight: 5200
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
## EmfPlusStringFormatFlags enumeration

The StringFormat flags specify options for graphics text layout, including direction, clipping and font handling. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum EmfPlusStringFormatFlags : uint
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StringFormatDirectionRightToLeft | `1` | If set, the reading order of the string SHOULD be right to left. For horizontal text, this means that characters are read from right to left. For vertical text, this means that columns are read from right to left. If clear, horizontal or vertical text SHOULD be read from left to right. |
| StringFormatDirectionVertical | `2` | If set, individual lines of text SHOULD be drawn vertically on the display device. If clear, individual lines of text SHOULD be drawn horizontally, with each new line below the previous line. |
| StringFormatNoFitBlackBox | `4` | If set, parts of characters MUST be allowed to overhang the text layout rectangle. If clear, characters that overhang the boundaries of the text layout rectangle MUST be repositioned to avoid overhang. An italic, "f" is an example of a character that can have overhanging parts. |
| StringFormatDisplayFormatControl | `20` | If set, control characters SHOULD appear in the output as representative Unicode glyphs. |
| StringFormatNoFontFallback | `400` | If set, an alternate font SHOULD be used for characters that are not supported in the requested font. If clear, a character missing from the requested font SHOULD appear as a "font missing" character, which MAY be an open square. |
| StringFormatMeasureTrailingSpaces | `800` | If set, the space at the end of each line MUST be included in measurements of string length. If clear, the space at the end of each line MUST be excluded from measurements of string length. |
| StringFormatNoWrap | `1000` | If set, a string that extends past the end of the text layout rectangle MUST NOT be wrapped to the next line. If clear, a string that extends past the end of the text layout rectangle MUST be broken at the last word boundary within the bounding rectangle, and the remainder of the string MUST be wrapped to the next line. |
| StringFormatLineLimit | `2000` | If set, whole lines of text SHOULD be output and SHOULD NOT be clipped by the string's layout rectangle. If clear, text layout SHOULD continue until all lines are output, or until additional lines would not be visible as a result of clipping. This flag can be used either to deny or allow a line of text to be partially obscured by a layout rectangle that is not a multiple of line height. For all text to be visible, a layout rectangle at least as tall as the height of one line. |
| StringFormatNoClip | `4000` | If set, text extending outside the string layout rectangle SHOULD be allowed to show. If clear, all text that extends outside the layout rectangle SHOULD be clipped. |
| StringFormatBypassGdi | `80000000` | This flag MAY be used to specify an implementation-specific process for rendering text. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


