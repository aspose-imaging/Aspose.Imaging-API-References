---
title: WmfVerticalTextAlignmentModeFlags
second_title: Aspose.Imaging for Java API Reference
description: VerticalTextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle for text alignment.
type: docs
weight: 37
url: /java/com.aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfVerticalTextAlignmentModeFlags extends System.Enum
```

VerticalTextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle, for text alignment. These flags can be combined to specify multiple options, with the restriction that only one flag can be chosen that alters the drawing position in the playback device context. Vertical text alignment is performed when the font has a vertical default baseline, such as Kanji.
## Fields

| Field | Description |
| --- | --- |
| [VTA_TOP](#VTA-TOP) | The reference point MUST be on the top edge of the bounding rectangle. |
| [VTA_RIGHT](#VTA-RIGHT) | The reference point MUST be on the right edge of the bounding rectangle. |
| [VTA_BOTTOM](#VTA-BOTTOM) | The reference point MUST be on the bottom edge of the bounding rectangle. |
| [VTA_CENTER](#VTA-CENTER) | The reference point MUST be aligned vertically with the center of the bounding rectangle. |
| [VTA_LEFT](#VTA-LEFT) | The reference point MUST be on the left edge of the bounding rectangle. |
| [VTA_BASELINE](#VTA-BASELINE) | The reference point MUST be on the baseline of the text. |
### VTA_TOP {#VTA-TOP}
```
public static final int VTA_TOP
```


The reference point MUST be on the top edge of the bounding rectangle.

### VTA_RIGHT {#VTA-RIGHT}
```
public static final int VTA_RIGHT
```


The reference point MUST be on the right edge of the bounding rectangle.

### VTA_BOTTOM {#VTA-BOTTOM}
```
public static final int VTA_BOTTOM
```


The reference point MUST be on the bottom edge of the bounding rectangle.

### VTA_CENTER {#VTA-CENTER}
```
public static final int VTA_CENTER
```


The reference point MUST be aligned vertically with the center of the bounding rectangle.

### VTA_LEFT {#VTA-LEFT}
```
public static final int VTA_LEFT
```


The reference point MUST be on the left edge of the bounding rectangle.

### VTA_BASELINE {#VTA-BASELINE}
```
public static final int VTA_BASELINE
```


The reference point MUST be on the baseline of the text.

