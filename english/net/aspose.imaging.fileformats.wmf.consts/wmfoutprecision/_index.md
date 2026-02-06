---
title: Enum WmfOutPrecision
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfOutPrecision enum. The OutPrecision enumeration defines values for output precision which is the requirement for the font mapper to match specific font parameters including height width character orientation escapement pitch and font type
type: docs
weight: 8440
url: /net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
## WmfOutPrecision enumeration

The OutPrecision enumeration defines values for output precision, which is the requirement for the font mapper to match specific font parameters, including height, width, character orientation, escapement, pitch, and font type.

```csharp
public enum WmfOutPrecision : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | A value that specifies default behavior. |
| String | `1` | A value that is returned when rasterized fonts are enumerated. |
| Stroke | `3` | A value that is returned when TrueType and other outline fonts, and vector fonts are enumerated. |
| Tt | `4` | A value that specifies the choice of a TrueType font when the system contains multiple fonts with the same name. |
| Device | `5` | A value that specifies the choice of a device font when the system contains multiple fonts with the same name. |
| Raster | `6` | A value that specifies the choice of a rasterized font when the system contains multiple fonts with the same name. |
| TtOnly | `7` | A value that specifies the requirement for only TrueType fonts. If there are no TrueType fonts installed in the system, default behavior is specified. |
| Outline | `8` | A value that specifies the requirement for TrueType and other outline fonts. |
| ScreenOutline | `9` | A value that specifies a preference for TrueType and other outline fonts. |
| PsOnly | `10` | A value that specifies a requirement for only PostScript fonts. If there are no PostScript fonts installed in the system, default behavior is specified. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


