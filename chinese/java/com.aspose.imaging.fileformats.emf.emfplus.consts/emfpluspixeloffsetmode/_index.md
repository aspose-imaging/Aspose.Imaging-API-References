---
title: "EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging for Java API 参考文档"
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

该 PixelOffsetMode 枚举定义像素的偏移方式，指定渲染速度与质量之间的权衡。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | 像素居中于整数坐标，优先速度而非质量。 |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | 像素居中于整数坐标，与 PixelOffsetModeNone 相同。 |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | 像素居中于半整数坐标，与 PixelOffsetModeHalf 相同。 |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | 像素居中于原点，这意味着像素覆盖 x 和 y 轴上从 -0.5 到 0.5 的区域，其中心位于 (0,0)。 |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | 像素居中于半整数坐标，这意味着像素覆盖 x 和 y 轴上从 0 到 1 的区域，其中心位于 (0.5,0.5)。 |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


像素居中于整数坐标，优先速度而非质量。

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


像素居中于整数坐标，与 PixelOffsetModeNone 相同。指定以更高速度牺牲质量。

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


像素居中于半整数坐标，与 PixelOffsetModeHalf 相同。指定以更高质量牺牲速度。

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


像素居中于原点，这意味着像素覆盖 x 和 y 轴上从 -0.5 到 0.5 的区域，其中心位于 (0,0)。

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


像素居中于半整数坐标，这意味着像素覆盖 x 和 y 轴上从 0 到 1 的区域，其中心位于 (0.5,0.5)。通过在渲染期间偏移像素，可以提升渲染质量，但会降低渲染速度。

