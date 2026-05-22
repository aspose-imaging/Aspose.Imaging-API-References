---
title: "枚举 EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusTextRenderingHint 枚举。TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这些会影响文本渲染的质量。"
type: docs
weight: 5220
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
## EmfPlusTextRenderingHint enumeration

TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这会影响文本渲染的质量。

```csharp
public enum EmfPlusTextRenderingHint : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| TextRenderingHintSystemDefault | `0` | 指定每个文本字符应使用操作系统上配置的字体平滑设置进行绘制。 |
| TextRenderingHintSingleBitPerPixelGridFit | `1` | 指定每个文本字符应使用其字形位图进行绘制。平滑可能被用于改善字符字形的笔画和曲线外观。 |
| TextRenderingHintSingleBitPerPixel | `2` | 指定每个文本字符应使用其字形位图进行绘制。不会使用平滑。 |
| TextRenderingHintAntialiasGridFit | `3` | 指定每个文本字符应使用带平滑的抗锯齿字形位图进行绘制。由于抗锯齿，渲染质量很高，但会带来更高的性能开销。 |
| TextRenderingHintAntialias | `4` | 指定每个文本字符使用未进行提示的抗锯齿字形位图进行绘制。抗锯齿可提升质量，但由于关闭了提示，笔画宽度差异可能会被注意到。 |
| TextRenderingHintClearTypeGridFit | `5` | 指定每个文本字符应使用带平滑的 ClearType 字形位图进行绘制。这是最高质量的文本提示设置，用于利用 ClearType 字体特性。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


