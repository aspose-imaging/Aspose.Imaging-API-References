---
title: StringFormatFlags
second_title: Aspose.Imaging for Java API Reference
description: Specifies the display and layout information for text strings.
type: docs
weight: 113
url: /java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Specifies the display and layout information for text strings.
## Fields

| Field | Description |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text is displayed from right to left. |
| [DirectionVertical](#DirectionVertical) | Text is vertically aligned. |
| [FitBlackBox](#FitBlackBox) | Parts of characters are allowed to overhang the string's layout rectangle. |
| [DisplayFormatControl](#DisplayFormatControl) | Control characters such as the left-to-right mark are shown in the output with a representative glyph. |
| [NoFontFallback](#NoFontFallback) | Fallback to alternate fonts for characters not supported in the requested font is disabled. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Includes the trailing space at the end of each line. |
| [NoWrap](#NoWrap) | Text wrapping between lines when formatting within a rectangle is disabled. |
| [LineLimit](#LineLimit) | Only entire lines are laid out in the formatting rectangle. |
| [NoClip](#NoClip) | Overhanging parts of glyphs, and unwrapped text reaching outside the formatting rectangle are allowed to show. |
| [ExactAlignment](#ExactAlignment) | The exact alignment, correct padding GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text is displayed from right to left.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text is vertically aligned.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Parts of characters are allowed to overhang the string's layout rectangle. By default, characters are repositioned to avoid any overhang.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Control characters such as the left-to-right mark are shown in the output with a representative glyph.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Fallback to alternate fonts for characters not supported in the requested font is disabled. Any missing characters are displayed with the fonts missing glyph, usually an open square.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Includes the trailing space at the end of each line. By default the boundary rectangle returned by the MeasureString method excludes the space at the end of each line. Set this flag to include that space in measurement.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Text wrapping between lines when formatting within a rectangle is disabled. This flag is implied when a point is passed instead of a rectangle, or when the specified rectangle has a zero line length.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Only entire lines are laid out in the formatting rectangle. By default layout continues until the end of the text, or until no more lines are visible as a result of clipping, whichever comes first. Note that the default settings allow the last line to be partially obscured by a formatting rectangle that is not a whole multiple of the line height. To ensure that only whole lines are seen, specify this value and be careful to provide a formatting rectangle at least as tall as the height of one line.

### NoClip {#NoClip}
```
public static final int NoClip
```


Overhanging parts of glyphs, and unwrapped text reaching outside the formatting rectangle are allowed to show. By default all text and glyph parts reaching outside the formatting rectangle are clipped.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


The exact alignment, correct padding GDI+

