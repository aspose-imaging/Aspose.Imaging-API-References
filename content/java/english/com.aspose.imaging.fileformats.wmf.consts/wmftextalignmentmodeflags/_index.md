---
title: WmfTextAlignmentModeFlags
second_title: Aspose.Imaging for Java API Reference
description: TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle for text alignment.
type: docs
weight: 36
url: /com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle, for text alignment. These flags can be combined to specify multiple options, with the restriction that only one flag can be chosen that alters the drawing position in the playback device context. Horizontal text alignment is performed when the font has a horizontal default baseline.

--------------------

TextAlignmentMode flags specify three different components of text alignment: - The horizontal position of the reference point is determined by TA\_RIGHT and TA\_CENTER; if those bits are clear, the alignment MUST be TA\_LEFT. - The vertical position of the reference point is determined by TA\_BOTTOM and TA\_BASELINE; if those bits are clear, the alignment MUST be TA\_TOP. - Whether to update the output position in the playback device context after text output is determined by TA\_UPDATECP; if that bit is clear, the position MUST NOT be updated. This is the reason for defining three different zero values in the enumeration; they represent the default states of the three components of text alignment.
## Fields

| Field | Description |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | The drawing position in the playback device context MUST NOT be updated after each text output call. |
| [Left](#Left) | The reference point MUST be on the left edge of the bounding rectangle. |
| [Top](#Top) | The reference point MUST be on the top edge of the bounding rectangle. |
| [Updatecp](#Updatecp) | The drawing position in the playback device context MUST be updated after each text output call. |
| [Right](#Right) | The reference point MUST be on the right edge of the bounding rectangle. |
| [Center](#Center) | The reference point MUST be aligned horizontally with the center of the bounding rectangle. |
| [Bottom](#Bottom) | The reference point MUST be on the bottom edge of the bounding rectangle. |
| [Baseline](#Baseline) | The reference point MUST be on the baseline of the text. |
| [Rtlreading](#Rtlreading) | The text MUST be laid out in right-to-left reading order, instead of the default left-to right order. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Center) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Baseline) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


The drawing position in the playback device context MUST NOT be updated after each text output call. The reference point MUST be passed to the text output function.

### Left {#Left}
```
public static final int Left
```


The reference point MUST be on the left edge of the bounding rectangle.

### Top {#Top}
```
public static final int Top
```


The reference point MUST be on the top edge of the bounding rectangle.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


The drawing position in the playback device context MUST be updated after each text output call. It MUST be used as the reference point.

### Right {#Right}
```
public static final int Right
```


The reference point MUST be on the right edge of the bounding rectangle.

### Center {#Center}
```
public static final int Center
```


The reference point MUST be aligned horizontally with the center of the bounding rectangle.

### Bottom {#Bottom}
```
public static final int Bottom
```


The reference point MUST be on the bottom edge of the bounding rectangle.

### Baseline {#Baseline}
```
public static final int Baseline
```


The reference point MUST be on the baseline of the text.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


The text MUST be laid out in right-to-left reading order, instead of the default left-to right order. This SHOULD be applied only when the font that is defined in the playback device context is either Hebrew or Arabic.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Represents Horizontal text align sets (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Represents Vertical text align sets (Top | Bottom | Baseline)

