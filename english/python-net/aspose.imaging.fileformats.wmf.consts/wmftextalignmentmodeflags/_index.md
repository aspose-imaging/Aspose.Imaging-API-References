---
title: WmfTextAlignmentModeFlags Enumeration
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---

TextAlignmentMode Flags specify the relationship between a reference point and a bounding<br/>                rectangle, for text alignment. These flags can be combined to specify multiple options, with the<br/>                restriction that only one flag can be chosen that alters the drawing position in the playback device<br/>                context.<br/>                Horizontal text alignment is performed when the font has a horizontal default baseline.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfTextAlignmentModeFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BASELINE | The reference point MUST be on the baseline of the text. |
| BOTTOM | The reference point MUST be on the bottom edge of the bounding rectangle. |
| CENTER | The reference point MUST be aligned horizontally with the center of the bounding rectangle. |
| HORIZONTAL | Represents Horizontal text algin sets (Left | Right | Center) |
| LEFT | The reference point MUST be on the left edge of the bounding rectangle. |
| NOUPDATECP | The drawing position in the playback device context MUST NOT be updated after each<br/>                text output call. The reference point MUST be passed to the text output function. |
| RIGHT | The reference point MUST be on the right edge of the bounding rectangle. |
| RTLREADING | The text MUST be laid out in right-to-left reading order, instead of the default left-to right order. This SHOULD<br/>                be applied only when the font that is defined in the playback<br/>                device context is either Hebrew or Arabic. |
| TOP | The reference point MUST be on the top edge of the bounding rectangle. |
| UPDATECP | The drawing position in the playback device context MUST be updated after each text<br/>                output call. It MUST be used as the reference point. |
| VERTICAL | Represents Vertical text align sets (Top | Bottom | Baseline) |
