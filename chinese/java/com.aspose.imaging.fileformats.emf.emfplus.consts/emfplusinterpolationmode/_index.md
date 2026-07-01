---
title: "EmfPlusInterpolationMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "InterpolationMode 枚举定义了执行缩放（包括拉伸和收缩）的方法。"
type: docs
weight: 29
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

InterpolationMode 枚举定义了执行缩放的方式，包括拉伸和收缩。
## 字段

| 字段 | 描述 |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | 指定默认的插值模式，其定义为 InterpolationModeBilinear。 |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | 指定低质量的插值模式，其定义为 InterpolationModeNearestNeighbor。 |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | 指定高质量的插值模式，其定义为 InterpolationModeHighQualityBicubic。 |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | 指定双线性插值，它使用围绕插值像素的最近 2x2 像素邻域。 |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | 指定双三次插值，它使用围绕插值像素的最近 4x4 像素邻域。 |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | 指定最近邻插值，它仅使用最接近插值像素的像素值。 |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | 指定带预过滤的双线性插值。 |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | 指定带预过滤的双三次插值，它在这些选项中产生最高质量的结果。 |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


指定默认的插值模式，其定义为 InterpolationModeBilinear。

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


指定低质量的插值模式，其定义为 InterpolationModeNearestNeighbor。

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


指定高质量的插值模式，其定义为 InterpolationModeHighQualityBicubic。

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


指定双线性插值，它使用围绕插值像素的最近 2x2 像素邻域。这 4 个已知像素值的加权平均决定插值像素的值。该结果比 InterpolationModeNearestNeighbor 更平滑。

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


指定双三次插值，它使用围绕插值像素的最近 4x4 像素邻域。这 16 个已知像素值的加权平均决定插值像素的值。由于已知像素与插值像素的距离不同，较近的像素在计算中赋予更高权重。该结果比 InterpolationModeBilinear 更平滑。

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


指定最近邻插值，它仅使用最接近插值像素的像素值。此模式仅复制或删除像素，产生这些选项中最低质量的结果。

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


指定带预过滤的双线性插值。

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


指定带预过滤的双三次插值，它在这些选项中产生最高质量的结果。

