---
title: "EmfPlusCurveAdjustments"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "CurveAdjustments 枚举定义可应用于图像颜色曲线的调整。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

CurveAdjustments 枚举定义可应用于图像颜色曲线的调整。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | 指定对图像曝光度的增减模拟。 |
| [AdjustDensity](#AdjustDensity) | 指定对图像密度的增减模拟。 |
| [AdjustContrast](#AdjustContrast) | 指定对图像对比度的增减。 |
| [AdjustHighlight](#AdjustHighlight) | 指定在颜色通道的值已高于半强度时，对图像该颜色通道的值进行增减。 |
| [AdjustShadow](#AdjustShadow) | 指定在颜色通道的值已低于半强度时，对图像该颜色通道的值进行增减。 |
| [AdjustMidtone](#AdjustMidtone) | 指定对图像进行增亮或加暗的调整。 |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | 指定对图像的白色饱和度进行调整，该饱和度定义为给定颜色通道强度范围中的最大值，通常范围为 0 到 255。 |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | 指定对图像的黑色饱和度进行调整，该饱和度是给定颜色通道强度范围中的最小值，通常范围为 0 到 255。 |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


指定对图像曝光度的增减模拟。

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


指定对图像密度的增减模拟。

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


指定对图像对比度的增减。

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


指定在颜色通道的值已高于强度一半时，对该通道的值进行增大或减小。此调整可用于在不影响暗区的情况下提升图像亮区的细节。

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


指定在颜色通道的值已低于强度一半时，对该通道的值进行增大或减小。此调整可用于在不影响亮区的情况下提升图像暗区的细节。

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


指定对图像进行提亮或加暗的调整。强度范围中部的颜色通道值会比接近最小或最大极值的通道值变化更大。此调整可在不失去图像最暗和最亮部分对比度的前提下，对图像进行提亮或加暗。

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


指定对图像的白色饱和度进行调整，该饱和度定义为给定颜色通道强度范围中的最大值，通常范围为 0 到 255。

--------------------

例如，白色饱和度调整值为 240 时，表示将 0 到 240 范围内的颜色通道值进行调整，使其分布到 0 到 255 的范围，且大于 240 的颜色通道值设为 255。

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


指定对图像的黑色饱和度进行调整，该饱和度是给定颜色通道强度范围中的最小值，通常范围为 0 到 255。

--------------------

例如，黑色饱和度调整值为 15 时，表示将 15 到 255 范围内的颜色通道值进行调整，使其分布到 0 到 255 的范围，且小于 15 的颜色通道值设为 0。

