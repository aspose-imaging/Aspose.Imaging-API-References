---
title: "EmfPlusCurveAdjustments"
second_title: "Aspose.Imaging for Java API 参考"
description: "CurveAdjustments 枚举定义了可应用于图像颜色曲线的调整。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

CurveAdjustments 枚举定义了可应用于图像颜色曲线的调整。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | 指定对图像曝光度的增加或减少的模拟。 |
| [AdjustDensity](#AdjustDensity) | 指定对图像密度的增加或减少的模拟。 |
| [AdjustContrast](#AdjustContrast) | 指定对图像对比度的增加或减少。 |
| [AdjustHighlight](#AdjustHighlight) | 指定对图像中颜色通道值的增加或减少，前提是该通道的值已高于强度的一半。 |
| [AdjustShadow](#AdjustShadow) | 指定对图像中颜色通道值的增加或减少，前提是该通道的值已低于强度的一半。 |
| [AdjustMidtone](#AdjustMidtone) | 指定对图像进行增亮或减暗的调整。 |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | 指定对图像白色饱和度的调整，定义为给定颜色通道在强度范围内的最大值，通常范围为 0 到 255。 |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | 指定对图像黑色饱和度的调整，即给定颜色通道在强度范围内的最小值，通常范围为 0 到 255。 |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


指定对图像曝光度的增加或减少的模拟。

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


指定对图像密度的增加或减少的模拟。

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


指定对图像对比度的增加或减少。

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


指定对图像中颜色通道值的增加或减少，前提是该通道的值已高于强度的一半。此调整可用于在不影响暗部的情况下提升图像亮部的细节。

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


指定对图像中颜色通道值的增加或减少，前提是该通道的值已低于强度的一半。此调整可用于在不影响亮部的情况下提升图像暗部的细节。

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


指定对图像进行增亮或减暗的调整。强度范围中部的颜色通道值比接近最小或最大极限的值变化更大。此调整可用于在不失去图像最暗和最亮部分对比度的情况下增亮或减暗图像。

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


指定对图像白色饱和度的调整，定义为给定颜色通道在强度范围内的最大值，通常范围为 0 到 255。

--------------------

例如，白色饱和度调整值为 240 表示将 0 到 240 范围内的颜色通道值调整，使其在 0 到 255 范围内展开，且大于 240 的颜色通道值设为 255。

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


指定对图像黑色饱和度的调整，即给定颜色通道在强度范围内的最小值，通常范围为 0 到 255。

--------------------

例如，黑色饱和度调整值为 15 表示将 15 到 255 范围内的颜色通道值调整，使其在 0 到 255 范围内展开，且小于 15 的颜色通道值设为 0。

