---
title: Enum EmfStretchMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStretchMode enum. The StretchMode enumeration is used to specify how color data is added to or removed from bitmaps that are stretched or compressed
type: docs
weight: 2960
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
## EmfStretchMode enumeration

The StretchMode enumeration is used to specify how color data is added to or removed from bitmaps that are stretched or compressed.

```csharp
public enum EmfStretchMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| STRETCH_ANDSCANS | `1` | Performs a Boolean AND operation using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves black pixels at the expense of white pixels |
| STRETCH_ORSCANS | `2` | Performs a Boolean OR operation using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves white pixels at the expense of black pixels. |
| STRETCH_DELETESCANS | `3` | Deletes the pixels. This mode deletes all eliminated lines of pixels without trying to preserve their information. |
| STRETCH_HALFTONE | `4` | Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. The average color over the destination block of pixels approximates the color of the source pixels. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


