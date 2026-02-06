---
title: Enum ColorComparisonMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.MagicWand.ColorComparisonMode enum. Specifies how colors are compared during the Magic Wand algorithm
type: docs
weight: 10780
url: /net/aspose.imaging.magicwand/colorcomparisonmode/
---
## ColorComparisonMode enumeration

Specifies how colors are compared during the Magic Wand algorithm.

```csharp
public enum ColorComparisonMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RgbDefault | `0` | Colors are compared in the RGB color space. Every color difference must satisfy the threshold. |
| YuvDefault | `1` | Colors are compared in the YUV color space. Every color difference must satisfy the threshold. |
| YuvLessLumaSensitive | `2` | Colors are compared in the YUV color space. Color information differences must satisfy the threshold, the threshold for luminance component is doubled. |
| Custom | `3` | Color comparison algorithm is defined by user. |

### See Also

* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


