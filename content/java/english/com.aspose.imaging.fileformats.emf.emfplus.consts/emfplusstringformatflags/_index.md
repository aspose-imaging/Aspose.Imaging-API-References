---
title: EmfPlusStringFormatFlags
second_title: Aspose.Imaging for Java API Reference
description: The StringFormat flags specify options for graphics text layout including direction clipping and font handling.
type: docs
weight: 50
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

The StringFormat flags specify options for graphics text layout, including direction, clipping and font handling. These flags can be combined to specify multiple options.
## Fields

| Field | Description |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | If set, the reading order of the string SHOULD be right to left. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | If set, individual lines of text SHOULD be drawn vertically on the display device. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | If set, parts of characters MUST be allowed to overhang the text layout rectangle. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | If set, control characters SHOULD appear in the output as representative Unicode glyphs. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | If set, an alternate font SHOULD be used for characters that are not supported in the requested font. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | If set, the space at the end of each line MUST be included in measurements of string length. |
| [StringFormatNoWrap](#StringFormatNoWrap) | If set, a string that extends past the end of the text layout rectangle MUST NOT be wrapped to the next line. |
| [StringFormatLineLimit](#StringFormatLineLimit) | If set, whole lines of text SHOULD be output and SHOULD NOT be clipped by the string's layout rectangle. |
| [StringFormatNoClip](#StringFormatNoClip) | If set, text extending outside the string layout rectangle SHOULD be allowed to show. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | This flag MAY be used to specify an implementation-specific process for rendering text. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


If set, the reading order of the string SHOULD be right to left. For horizontal text, this means that characters are read from right to left. For vertical text, this means that columns are read from right to left. If clear, horizontal or vertical text SHOULD be read from left to right.

--------------------

Graphics text layout is specified by [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat) objects

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


If set, individual lines of text SHOULD be drawn vertically on the display device. If clear, individual lines of text SHOULD be drawn horizontally, with each new line below the previous line.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


If set, parts of characters MUST be allowed to overhang the text layout rectangle. If clear, characters that overhang the boundaries of the text layout rectangle MUST be repositioned to avoid overhang. An italic, "f" is an example of a character that can have overhanging parts.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


If set, control characters SHOULD appear in the output as representative Unicode glyphs.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


If set, an alternate font SHOULD be used for characters that are not supported in the requested font. If clear, a character missing from the requested font SHOULD appear as a "font missing" character, which MAY be an open square.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


If set, the space at the end of each line MUST be included in measurements of string length. If clear, the space at the end of each line MUST be excluded from measurements of string length.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


If set, a string that extends past the end of the text layout rectangle MUST NOT be wrapped to the next line. If clear, a string that extends past the end of the text layout rectangle MUST be broken at the last word boundary within the bounding rectangle, and the remainder of the string MUST be wrapped to the next line.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


If set, whole lines of text SHOULD be output and SHOULD NOT be clipped by the string's layout rectangle. If clear, text layout SHOULD continue until all lines are output, or until additional lines would not be visible as a result of clipping. This flag can be used either to deny or allow a line of text to be partially obscured by a layout rectangle that is not a multiple of line height. For all text to be visible, a layout rectangle at least as tall as the height of one line.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


If set, text extending outside the string layout rectangle SHOULD be allowed to show. If clear, all text that extends outside the layout rectangle SHOULD be clipped.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


This flag MAY be used to specify an implementation-specific process for rendering text.

