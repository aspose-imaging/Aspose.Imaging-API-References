---
title: "WmfOutPrecision"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "OutPrecision 枚举定义了输出精度的值，该精度是字体映射器匹配特定字体参数（包括高度、宽度、字符方向、倾斜、间距和字体类型）的要求。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfOutPrecision extends System.Enum
```

OutPrecision 枚举定义输出精度的值，这是字体映射器匹配特定字体参数（包括高度、宽度、字符方向、倾斜角度、字距和字体类型）的要求。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 指定默认行为的值。 |
| [String](#String) | 在枚举光栅化字体时返回的值。 |
| [Stroke](#Stroke) | 在枚举 TrueType 及其他轮廓字体和矢量字体时返回的值。 |
| [Tt](#Tt) | 指定在系统中存在同名多个字体时选择 TrueType 字体的值。 |
| [Device](#Device) | 指定在系统中存在同名多个字体时选择设备字体的值。 |
| [Raster](#Raster) | 指定在系统中存在同名多个字体时选择光栅化字体的值。 |
| [TtOnly](#TtOnly) | 指定仅需 TrueType 字体的要求的值。 |
| [Outline](#Outline) | 指定对 TrueType 及其他轮廓字体的要求的值。 |
| [ScreenOutline](#ScreenOutline) | 指定对 TrueType 及其他轮廓字体的偏好的值。 |
| [PsOnly](#PsOnly) | 指定仅需 PostScript 字体的要求的值。 |
### Default {#Default}
```
public static final byte Default
```


指定默认行为的值。

### String {#String}
```
public static final byte String
```


在枚举光栅化字体时返回的值。

### Stroke {#Stroke}
```
public static final byte Stroke
```


在枚举 TrueType 及其他轮廓字体和矢量字体时返回的值。

### Tt {#Tt}
```
public static final byte Tt
```


指定在系统中存在同名多个字体时选择 TrueType 字体的值。

### Device {#Device}
```
public static final byte Device
```


指定在系统中存在同名多个字体时选择设备字体的值。

### Raster {#Raster}
```
public static final byte Raster
```


指定在系统中存在同名多个字体时选择光栅化字体的值。

### TtOnly {#TtOnly}
```
public static final byte TtOnly
```


指定仅需 TrueType 字体的要求的值。如果系统中未安装 TrueType 字体，则指定默认行为。

### Outline {#Outline}
```
public static final byte Outline
```


指定对 TrueType 及其他轮廓字体的要求的值。

### ScreenOutline {#ScreenOutline}
```
public static final byte ScreenOutline
```


指定对 TrueType 及其他轮廓字体的偏好的值。

### PsOnly {#PsOnly}
```
public static final byte PsOnly
```


指定仅需 PostScript 字体的要求的值。如果系统中未安装 PostScript 字体，则指定默认行为。

