---
title: "EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这会影响文本渲染的质量。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

该 TextRenderingHint 枚举定义文本提示和抗锯齿的类型，这会影响文本渲染的质量。
## 字段

| 字段 | 描述 |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | 指定每个文本字符 SHOULD 使用操作系统上配置的字体平滑设置进行绘制。 |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | 指定每个文本字符 SHOULD 使用其字形位图进行绘制。 |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | 指定每个文本字符 SHOULD 使用其字形位图进行绘制。 |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | 指定每个文本字符 SHOULD 使用其带平滑的抗锯齿字形位图进行绘制。 |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | 指定每个文本字符使用其抗锯齿字形位图进行绘制，且不使用提示。 |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | 指定每个文本字符 SHOULD 使用其 ClearType 字形位图并进行平滑处理。 |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


指定每个文本字符 SHOULD 使用操作系统上配置的字体平滑设置进行绘制。

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


指定每个文本字符 SHOULD 使用其字形位图进行绘制。Smoothing MAY 用于改善字符字形的笔画和曲线外观。

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


指定每个文本字符 SHOULD 使用其字形位图进行绘制。不使用平滑。

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


指定每个文本字符 SHOULD 使用其带平滑的抗锯齿字形位图进行绘制。由于抗锯齿，渲染质量高，但性能成本更高。

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


指定每个文本字符使用其带抗锯齿的字形位图进行绘制，且不使用提示。抗锯齿可获得更好的质量，但笔画宽度差异 MAY 被注意到，因为提示已关闭。

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


指定每个文本字符 SHOULD 使用其 ClearType 字形位图并进行平滑处理。这是最高质量的文本提示设置，用于利用 ClearType 字体特性。

