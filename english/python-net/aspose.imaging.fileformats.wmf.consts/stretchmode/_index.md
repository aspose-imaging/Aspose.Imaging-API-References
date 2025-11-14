---
title: StretchMode Enumeration
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---

The [StretchMode](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/) Enumeration specifies the bitmap<br/>                stretching mode, which defines how the system combines rows or columns<br/>                of a bitmap with existing pixels.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.StretchMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BLACK_ON_WHITE | Performs a Boolean AND operation by using the color values for the<br/>                eliminated and existing pixels. If the bitmap is a monochrome<br/>                bitmap, this mode preserves black pixels at the expense of white<br/>                pixels |
| COLOR_ON_COLOR | Deletes the pixels. This mode deletes all eliminated lines of pixels<br/>                without trying to preserve their information. |
| HALF_TONE | Maps pixels from the source rectangle into blocks of pixels in the<br/>                destination rectangle. The average color over the destination block<br/>                of pixels approximates the color of the source pixels. |
| WHITE_ON_BLACK | Performs a Boolean OR operation by using the color values for the<br/>                eliminated and existing pixels. If the bitmap is a monochrome<br/>                bitmap, this mode preserves white pixels at the expense of black<br/>                pixels |
