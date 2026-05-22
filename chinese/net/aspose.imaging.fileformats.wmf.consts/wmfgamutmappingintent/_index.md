---
title: "枚举 WmfGamutMappingIntent"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfGamutMappingIntent 枚举。GamutMappingIntent 枚举指定逻辑颜色与物理颜色之间的关系。"
type: docs
weight: 8370
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
## WmfGamutMappingIntent enumeration

此 GamutMappingIntent 枚举指定逻辑颜色与物理颜色之间的关系。

```csharp
[Flags]
public enum WmfGamutMappingIntent
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| LCS_GM_ABS_COLORIMETRIC | `8` | 指定应保持白点。通常在逻辑颜色必须匹配到目标色域中最近的物理颜色时使用。意图：Match ICC 名称：Absolute Colorimetric |
| LCS_GM_BUSINESS | `1` | 指定应保持饱和度。通常用于商业图表及其他不需要抖动的场景。意图：Graphic ICC 名称：Saturation |
| LCS_GM_GRAPHICS | `2` | 指定应保持色度匹配。通常用于图形设计和命名颜色。意图：Proof ICC 名称：Relative Colorimetric |
| LCS_GM_IMAGES | `4` | 指定应保持对比度。通常用于照片和自然图像。意图：Picture ICC 名称：Perceptual |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


