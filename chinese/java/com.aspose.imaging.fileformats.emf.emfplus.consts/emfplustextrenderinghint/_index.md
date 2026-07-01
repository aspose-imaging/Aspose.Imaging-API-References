---
title: "EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging for Java API 参考"
description: "TextRenderingHint 枚举定义了文本提示和抗锯齿的类型，这些会影响文本渲染的质量。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

TextRenderingHint 枚举定义文本提示和抗锯齿的类型，这会影响文本渲染的质量。
## 字段

| 字段 | 描述 |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | 指定每个文本字符应使用操作系统上配置的字体平滑设置进行绘制。 |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | 指定每个文本字符应使用其字形位图进行绘制。 |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | 指定每个文本字符应使用其字形位图进行绘制。 |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | 指定每个文本字符应使用其抗锯齿字形位图并进行平滑绘制。 |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | 指定每个文本字符使用其抗锯齿字形位图绘制，且不进行提示。 |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | 指定每个文本字符应使用其 ClearType 字形位图并进行平滑绘制。 |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


指定每个文本字符应使用操作系统上配置的字体平滑设置进行绘制。

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


指定每个文本字符应使用其字形位图绘制。平滑可用于改善字符字形笔干和曲线的外观。

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


指定每个文本字符应使用其字形位图绘制。不会使用平滑。

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


指定每个文本字符应使用其抗锯齿字形位图并进行平滑绘制。由于抗锯齿，渲染质量很高，但性能开销更大。

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


指定每个文本字符使用其抗锯齿字形位图绘制，且不进行提示。抗锯齿可提供更好的质量，但由于关闭提示，笔干宽度差异可能会显现。

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


指定每个文本字符应使用其 ClearType 字形位图并进行平滑绘制。这是最高质量的文本提示设置，用于利用 ClearType 字体特性。

