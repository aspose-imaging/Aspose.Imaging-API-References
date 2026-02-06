---
title: Enum WmfGamutMappingIntent
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfGamutMappingIntent enum. The GamutMappingIntent Enumeration specifies the relationship between logical and physical colors
type: docs
weight: 8370
url: /net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
## WmfGamutMappingIntent enumeration

The GamutMappingIntent Enumeration specifies the relationship between logical and physical colors.

```csharp
[Flags]
public enum WmfGamutMappingIntent
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| LCS_GM_ABS_COLORIMETRIC | `8` | Specifies that the white point SHOULD be maintained. Typically used when logical colors MUST be matched to their nearest physical color in the destination color gamut. Intent: Match ICC name: Absolute Colorimetric |
| LCS_GM_BUSINESS | `1` | Specifies that saturation SHOULD be maintained. Typically used for business charts and other situations in which dithering is not required. Intent: Graphic ICC name: Saturation |
| LCS_GM_GRAPHICS | `2` | Specifies that a colorimetric match SHOULD be maintained. Typically used for graphic designs and named colors. Intent: Proof ICC name: Relative Colorimetric |
| LCS_GM_IMAGES | `4` | Specifies that contrast SHOULD be maintained. Typically used for photographs and natural images. Intent: Picture ICC name: Perceptual |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


