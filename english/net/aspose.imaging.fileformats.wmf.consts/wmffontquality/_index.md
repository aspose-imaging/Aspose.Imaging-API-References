---
title: Enum WmfFontQuality
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfFontQuality enum. The FontQuality Enumeration specifies how closely the attributes of the logical font should match those of the physical font when rendering text
type: docs
weight: 8360
url: /net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

The FontQuality Enumeration specifies how closely the attributes of the logical font should match those of the physical font when rendering text.

```csharp
public enum WmfFontQuality : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | Specifies that the character quality of the font does not matter, so DRAFT can be used. |
| Draft | `1` | Specifies that the character quality of the font is less important than the matching of logical attribuetes. For rasterized fonts, scaling SHOULD be enabled, which means that more font sizes are available. |
| Proof | `2` | Specifies that the character quality of the font is more important than the matching of logical attributes. For rasterized fonts, scaling SHOULD be disabled, and the font closest in size SHOULD be chosen. |
| Nonantialiased | `3` | Specifies that anti-aliasing SHOULD NOT be used when rendering text |
| Antialiased | `4` | Specifies that anti-aliasing SHOULD be used when rendering text, if the font supports it. |
| Cleartype | `5` | Specifies that ClearType anti-aliasing SHOULD be used when rendering text, if the font supports it. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


