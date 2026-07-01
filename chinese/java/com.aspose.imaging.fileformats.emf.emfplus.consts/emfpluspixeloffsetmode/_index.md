---
title: "EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "PixelOffsetMode 枚举定义了像素的偏移方式，指定了渲染速度与质量之间的权衡。"
type: docs
weight: 44
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

PixelOffsetMode 枚举定义像素的偏移方式，它指定了渲染速度与质量之间的权衡。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | 像素以整数坐标为中心，优先考虑速度而非质量。 |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | 像素以整数坐标为中心，正如 PixelOffsetModeNone 所示。 |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | 像素以半整数坐标为中心，正如 PixelOffsetModeHalf 所示。 |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | 像素以原点为中心，这意味着像素在 x 和 y 轴上覆盖从 -0.5 到 0.5 的区域，其中心位于 (0,0)。 |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | 像素以半整数坐标为中心，这意味着像素在 x 和 y 轴上覆盖从 0 到 1 的区域，其中心位于 (0.5,0.5)。 |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


像素以整数坐标为中心，优先考虑速度而非质量。

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


像素以整数坐标为中心，正如 PixelOffsetModeNone 所示。指定以牺牲质量为代价的更高速度。

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


像素以半整数坐标为中心，正如 PixelOffsetModeHalf 所示。指定以牺牲速度为代价的更高质量。

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


像素以原点为中心，这意味着像素在 x 和 y 轴上覆盖从 -0.5 到 0.5 的区域，其中心位于 (0,0)。

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


像素以半整数坐标为中心，这意味着像素在 x 和 y 轴上覆盖从 0 到 1 的区域，其中心位于 (0.5,0.5)。通过在渲染过程中偏移像素，可以在牺牲渲染速度的代价下提升渲染质量。

