---
title: "InterpolationMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 com.aspose.imaging.InterpolationMode 枚举指定在对图像进行缩放或旋转时使用的算法。"
type: docs
weight: 65
url: /zh/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

`com.aspose.imaging.InterpolationMode` 枚举指定在对图像进行缩放或旋转时使用的算法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Invalid](#Invalid) | 无效的插值模式。 |
| [Default](#Default) | 指定默认模式。 |
| [Low](#Low) | 指定低质量插值。 |
| [High](#High) | 指定高质量插值。 |
| [Bilinear](#Bilinear) | 指定双线性插值。 |
| [Bicubic](#Bicubic) | 指定双三次插值。 |
| [NearestNeighbor](#NearestNeighbor) | 指定最近邻插值。 |
| [HighQualityBilinear](#HighQualityBilinear) | 指定高质量双线性插值。 |
| [HighQualityBicubic](#HighQualityBicubic) | 指定高质量双三次插值。 |
### Invalid {#Invalid}
```
public static final int Invalid
```


无效的插值模式。

### Default {#Default}
```
public static final int Default
```


指定默认模式。

### Low {#Low}
```
public static final int Low
```


指定低质量插值。

### High {#High}
```
public static final int High
```


指定高质量插值。

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


指定双线性插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 50% 以下。

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


指定双三次插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 25% 以下。

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


指定最近邻插值。

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


指定高质量双线性插值。进行预过滤以确保高质量缩小。

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


指定高质量双三次插值。进行预过滤以确保高质量缩小。此模式产生最高质量的变换图像。

