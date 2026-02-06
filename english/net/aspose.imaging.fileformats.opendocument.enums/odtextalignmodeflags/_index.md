---
title: Enum OdTextAlignModeFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.OpenDocument.Enums.OdTextAlignModeFlags enum. The open document text align mode flags
type: docs
weight: 6990
url: /net/aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
## OdTextAlignModeFlags enumeration

The open document text align mode flags

```csharp
[Flags]
public enum OdTextAlignModeFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Noupdatecp | `0` | The drawing position in the playback device context MUST NOT be updated after each text output call. The reference point MUST be passed to the text output function. |
| Left | `0` | The reference point MUST be on the left edge of the bounding rectangle. |
| Top | `0` | The reference point MUST be on the top edge of the bounding rectangle. |
| Updatecp | `0` | The drawing position in the playback device context MUST be updated after each text output call. It MUST be used as the reference point. |
| Right | `1` | The reference point MUST be on the right edge of the bounding rectangle. |
| Center | `2` | The reference point MUST be aligned horizontally with the center of the bounding rectangle. |
| Justify | `4` | The text must be aligned in a way each text line of a paragraph has the same length. |
| Bottom | `8` | The reference point MUST be on the bottom edge of the bounding rectangle. |
| Baseline | `10` | The reference point MUST be on the baseline of the text. |
| Rtlreading | `100` | The text MUST be laid out in right-to-left reading order, instead of the default left-to right order. This SHOULD be applied only when the font that is defined in the playback device context is either Hebrew or Arabic. |
| Horizontal | `3` | Represents Horisontal text algin sets (Left &#x7C; Right &#x7C; Center) |
| Vertical | `18` | Represents Vertical text algin sets (Top &#x7C; Bottom &#x7C; Baseline) |

### See Also

* namespace [Aspose.Imaging.FileFormats.OpenDocument.Enums](../../aspose.imaging.fileformats.opendocument.enums/)
* assembly [Aspose.Imaging](../../)


