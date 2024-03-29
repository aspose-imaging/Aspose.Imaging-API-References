---
title: EmfPlusTextRenderingHint
second_title: Aspose.Imaging for .NET API 参考
description: TextRenderingHint 枚举定义了文本提示和抗锯齿的类型这会影响文本渲染的质量
type: docs
weight: 5100
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
## EmfPlusTextRenderingHint enumeration

TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这会影响文本渲染的质量。

```csharp
public enum EmfPlusTextRenderingHint : byte
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| TextRenderingHintSystemDefault | `0` | 指定应该使用操作系统上配置的任何字体平滑设置来绘制每个文本字符。 |
| TextRenderingHintSingleBitPerPixelGridFit | `1` | 指定每个文本字符应该使用其字形位图绘制。平滑可用于改善字符字形词干和曲率的外观。 |
| TextRenderingHintSingleBitPerPixel | `2` | 指定每个文本字符应该使用其字形位图绘制。不使用平滑。 |
| TextRenderingHintAntialiasGridFit | `3` | 指定每个文本字符应该使用其抗锯齿字形位图和平滑来绘制。由于抗锯齿，渲染质量很高，但性能成本更高。 |
| TextRenderingHintAntialias | `4` | 指定每个文本字符都是使用其抗锯齿字形位图绘制的，没有提示。抗锯齿带来更好的质量，但由于关闭了提示，因此词干宽度差异可能很明显。 |
| TextRenderingHintClearTypeGridFit | `5` | 指定每个文本字符都应该使用其 ClearType 字形位图进行平滑绘制。这是最高质量的文本提示设置，用于利用 ClearType 字体功能。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
