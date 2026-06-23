---
title: "EmfPlusCompositingQuality"
second_title: "Aspose.Imaging for Java API 参考"
description: "CompositingQuality 枚举定义了创建复合图像的质量等级。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

CompositingQuality 枚举定义了创建复合图像的质量等级。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | 未执行伽马校正。 |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | 未执行伽马校正。 |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | 已执行伽马校正。 |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | 启用伽马校正以获得更高质量的合成，但速度较慢。 |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | 未执行伽马校正；然而，使用线性值比默认值在稍低的速度下提供更好的质量。 |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


未执行伽马校正。伽马校正控制图像的整体亮度和对比度。没有伽马校正，合成图像可能显得过亮或过暗。

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


未执行伽马校正。合成速度优先于质量。在结果上，此值与 CompositingQualityDefault 没有区别。

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


已执行伽马校正。合成质量优先于速度。

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


启用伽马校正以获得更高质量的合成，但速度较慢。在结果上，此值与 CompositingQualityHighQuality 没有区别。

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


未执行伽马校正；然而，使用线性值比默认值在稍低的速度下提供更好的质量。

