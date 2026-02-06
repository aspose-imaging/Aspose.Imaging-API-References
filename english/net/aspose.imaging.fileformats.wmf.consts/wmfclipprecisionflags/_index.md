---
title: Enum WmfClipPrecisionFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfClipPrecisionFlags enum. ClipPrecision Flags specify clipping precision which defines how to clip characters that are partially outside a clipping region. These flags can be combined to specify multiple options
type: docs
weight: 8310
url: /net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

ClipPrecision Flags specify clipping precision, which defines how to clip characters that are partially outside a clipping region. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | Specifies that default clipping MUST be used. |
| Character | `1` | This value SHOULD NOT be used. |
| Stroke | `2` | This value MAY be returned when enumerating rasterized, TrueType and vector fonts. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000, and Windows XP: This value is always returned when enumerating fonts.) |
| LhAngles | `10` | This value is used to control font rotation, as follows: - If set, the rotation for all fonts SHOULD be determined by the orientation of the coordinate system; that is, whether the orientation is left-handed or right-handed. - If clear, device fonts SHOULD rotate counterclockwise, but the rotation of other fonts SHOULD be determined by the orientation of the coordinate system. |
| TtAlways | `20` | This value SHOULD NOT [34] be used. [34] This value is ignored in the following Windows versions: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | This value specifies that font association SHOULD [35] be turned off. [35] This value is not supported.in Windows 95, Windows 98, and Windows Millennium Edition. Font association is turned off in Windows 2000, Windows XP, and Windows Server 2003. This value is ignored in these Windows versions: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| Embedded | `80` | This value specifies that font embedding MUST be used to render document content; embedded fonts are read-only. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


