---
title: "EmfPlusFilterType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "FilterType 枚举定义了可用于文本和图形质量提升以及图像渲染的过滤算法类型。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

FilterType 枚举定义了可用于文本和图形质量提升以及图像渲染的过滤算法类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | 指定不执行过滤。 |
| [FilterTypePoint](#FilterTypePoint) | 指定通过从源图像采样最近像素来计算每个目标像素。 |
| [FilterTypeLinear](#FilterTypeLinear) | 指定使用源像素周围 2×2 区域像素的加权平均进行线性插值。 |
| [FilterTypeTriangle](#FilterTypeTriangle) | 指定源图像中的每个像素对目标图像的贡献相等。 |
| [FilterTypeBox](#FilterTypeBox) | 指定盒式过滤算法，其中每个目标像素通过对一矩形区域的源像素取平均来计算。 |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | 指定使用 4 采样的锥形过滤器。 |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | 指定使用 4 采样的高斯过滤器，可在图像上产生模糊效果。 |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


指定不执行过滤。

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


指定通过从源图像采样最近像素来计算每个目标像素。

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


指定使用源像素周围 2×2 区域像素的加权平均进行线性插值。

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


指定源图像中的每个像素对目标图像的贡献相等。这是所有过滤算法中最慢的。

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


指定一种盒式滤波算法，其中每个目标像素通过对源像素矩形进行平均来计算。该算法仅在缩小图像尺寸时有用。

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


指定使用 4 采样的锥形过滤器。

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


指定使用 4 采样的高斯过滤器，可在图像上产生模糊效果。

