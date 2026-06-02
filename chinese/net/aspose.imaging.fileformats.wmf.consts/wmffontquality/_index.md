---
title: "枚举 WmfFontQuality"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfFontQuality 枚举。FontQuality 枚举指定在渲染文本时，逻辑字体的属性应与物理字体的属性匹配的程度。"
type: docs
weight: 8360
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

此 FontQuality 枚举指定在渲染文本时，逻辑字体的属性应与物理字体的属性匹配的程度。

```csharp
public enum WmfFontQuality : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 指定字体的字符质量不重要，因此可以使用 DRAFT。 |
| Draft | `1` | 指定字体的字符质量不如逻辑属性的匹配重要。对于光栅化字体，应该启用缩放，这意味着可用的字体尺寸更多。 |
| Proof | `2` | 指定字体的字符质量比逻辑属性的匹配更重要。对于光栅化字体，应该禁用缩放，并应选择尺寸最接近的字体。 |
| Nonantialiased | `3` | 指定在渲染文本时不应使用抗锯齿 |
| Antialiased | `4` | 指定在渲染文本时应使用抗锯齿（如果字体支持）。 |
| Cleartype | `5` | 指定在渲染文本时应使用 ClearType 抗锯齿（如果字体支持）。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


