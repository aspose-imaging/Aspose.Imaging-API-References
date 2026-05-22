---
title: "枚举 WmfOutPrecision"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfOutPrecision 枚举。OutPrecision 枚举定义了输出精度的取值，这是一种对字体映射器匹配特定字体参数（包括高度、宽度、字符方向、倾斜角度、间距和字体类型）的要求。"
type: docs
weight: 8440
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
## WmfOutPrecision enumeration

此 OutPrecision 枚举定义了输出精度的值，即字体映射器匹配特定字体参数（包括高度、宽度、字符方向、倾斜、字距和字体类型）的要求。

```csharp
public enum WmfOutPrecision : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 指定默认行为的值。 |
| String | `1` | 在枚举栅格化字体时返回的值。 |
| Stroke | `3` | 在枚举 TrueType 及其他轮廓字体和矢量字体时返回的值。 |
| Tt | `4` | 当系统中存在多个同名字体时，指定 TrueType 字体选择的值。 |
| Device | `5` | 当系统中存在多个同名字体时，指定设备字体选择的值。 |
| Raster | `6` | 当系统中存在多个同名字体时，指定光栅化字体选择的值。 |
| TtOnly | `7` | 指定仅限 TrueType 字体的要求的值。如果系统中未安装 TrueType 字体，则使用默认行为。 |
| Outline | `8` | 指定对 TrueType 及其他轮廓字体的要求的值。 |
| ScreenOutline | `9` | 指定对 TrueType 及其他轮廓字体的首选项的值。 |
| PsOnly | `10` | 指定仅限 PostScript 字体的要求的值。如果系统中未安装 PostScript 字体，则使用默认行为。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


