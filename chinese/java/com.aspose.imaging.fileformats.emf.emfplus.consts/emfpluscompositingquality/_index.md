---
title: "EmfPlusCompositingQuality"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "CompositingQuality 枚举定义创建复合图像的质量级别。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

CompositingQuality 枚举定义创建复合图像的质量级别。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | 未执行伽马校正。 |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | 未执行伽马校正。 |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | 已执行伽马校正。 |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | 启用伽马校正以获得更高质量的合成，但速度较慢。 |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | 未执行伽马校正；然而，使用线性值可在略低的速度下获得比默认更好的质量。 |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


未执行伽马校正。伽马校正控制图像的整体亮度和对比度。若未进行伽马校正，合成图像可能显得过亮或过暗。

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


未执行伽马校正。合成速度优先，牺牲质量。从结果来看，此值与 CompositingQualityDefault 没有区别。

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


已执行伽马校正。合成质量优先，牺牲速度。

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


启用伽马校正以获得更高质量的合成，但速度较慢。从结果来看，此值与 CompositingQualityHighQuality 没有区别。

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


未执行伽马校正；然而，使用线性值可在略低的速度下获得比默认更好的质量。

