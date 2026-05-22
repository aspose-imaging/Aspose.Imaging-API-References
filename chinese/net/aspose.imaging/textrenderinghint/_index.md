---
title: "枚举 TextRenderingHint"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.TextRenderingHint 枚举。指定文本渲染的质量"
type: docs
weight: 11780
url: /zh/net/aspose.imaging/textrenderinghint/
---
## TextRenderingHint enumeration

指定文本渲染的质量。

```csharp
public enum TextRenderingHint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SystemDefault | `0` | 每个字符使用其字形位图绘制，采用系统默认的渲染提示。文本将按照用户为系统选择的字体平滑设置进行绘制。 |
| SingleBitPerPixelGridFit | `1` | 每个字符使用其字形位图绘制。提示用于改善字符在笔画和曲线上的外观。 |
| SingleBitPerPixel | `2` | 每个字符使用其字形位图绘制。未使用提示。 |
| AntiAliasGridFit | `3` | 每个字符使用带有提示的抗锯齿字形位图绘制。由于抗锯齿，质量大幅提升，但性能开销更高。 |
| AntiAlias | `4` | 每个字符使用未带提示的抗锯齿字形位图绘制。由于抗锯齿，质量更好。由于关闭提示，笔画宽度差异可能会更明显。 |
| ClearTypeGridFit | `5` | 每个字符使用带有提示的 ClearType 字形位图绘制。最高质量设置。用于利用 ClearType 字体特性。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


