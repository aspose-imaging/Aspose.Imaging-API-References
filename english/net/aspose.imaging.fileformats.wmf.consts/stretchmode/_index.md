---
title: Enum StretchMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.StretchMode enum. The StretchMode Enumeration specifies the bitmap stretching mode which defines how the system combines rows or columns of a bitmap with existing pixels
type: docs
weight: 8270
url: /net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---
## StretchMode enumeration

The `StretchMode` Enumeration specifies the bitmap stretching mode, which defines how the system combines rows or columns of a bitmap with existing pixels.

```csharp
public enum StretchMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| BlackOnWhite | `1` | Performs a Boolean AND operation by using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves black pixels at the expense of white pixels |
| WhiteOnBlack | `2` | Performs a Boolean OR operation by using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves white pixels at the expense of black pixels |
| ColorOnColor | `3` | Deletes the pixels. This mode deletes all eliminated lines of pixels without trying to preserve their information. |
| HalfTone | `4` | Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. The average color over the destination block of pixels approximates the color of the source pixels. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


