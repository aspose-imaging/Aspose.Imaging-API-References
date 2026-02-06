---
title: Enum WmfTextAlignmentModeFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfTextAlignmentModeFlags enum. TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle for text alignment. These flags can be combined to specify multiple options with the restriction that only one flag can be chosen that alters the drawing position in the playback device context. Horizontal text alignment is performed when the font has a horizontal default baseline
type: docs
weight: 8530
url: /net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
## WmfTextAlignmentModeFlags enumeration

TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle, for text alignment. These flags can be combined to specify multiple options, with the restriction that only one flag can be chosen that alters the drawing position in the playback device context. Horizontal text alignment is performed when the font has a horizontal default baseline.

```csharp
[Flags]
public enum WmfTextAlignmentModeFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Noupdatecp | `0` | The drawing position in the playback device context MUST NOT be updated after each text output call. The reference point MUST be passed to the text output function. |
| Left | `0` | The reference point MUST be on the left edge of the bounding rectangle. |
| Top | `0` | The reference point MUST be on the top edge of the bounding rectangle. |
| Updatecp | `1` | The drawing position in the playback device context MUST be updated after each text output call. It MUST be used as the reference point. |
| Right | `2` | The reference point MUST be on the right edge of the bounding rectangle. |
| Center | `6` | The reference point MUST be aligned horizontally with the center of the bounding rectangle. |
| Bottom | `8` | The reference point MUST be on the bottom edge of the bounding rectangle. |
| Baseline | `18` | The reference point MUST be on the baseline of the text. |
| Rtlreading | `100` | The text MUST be laid out in right-to-left reading order, instead of the default left-to right order. This SHOULD be applied only when the font that is defined in the playback device context is either Hebrew or Arabic. |
| Horizontal | `6` | Represents Horizontal text algin sets (Left &#x7C; Right &#x7C; Center) |
| Vertical | `18` | Represents Vertical text align sets (Top &#x7C; Bottom &#x7C; Baseline) |

## Remarks

TextAlignmentMode flags specify three different components of text alignment: - The horizontal position of the reference point is determined by TA_RIGHT and TA_CENTER; if those bits are clear, the alignment MUST be TA_LEFT. - The vertical position of the reference point is determined by TA_BOTTOM and TA_BASELINE; if those bits are clear, the alignment MUST be TA_TOP. - Whether to update the output position in the playback device context after text output is determined by TA_UPDATECP; if that bit is clear, the position MUST NOT be updated. This is the reason for defining three different zero values in the enumeration; they represent the default states of the three components of text alignment.

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


