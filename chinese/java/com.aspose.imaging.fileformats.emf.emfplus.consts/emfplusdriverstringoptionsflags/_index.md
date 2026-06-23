---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Aspose.Imaging for Java API 参考"
description: "DriverStringOptions 标志指定了图形文本定位和渲染的属性。"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

DriverStringOptions 标志指定图形文本定位和渲染的属性。这些标志可以组合以指定多个选项。

--------------------

图形文本输出在 [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring) 记录中指定。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | 如果设置，则字符字形的位置应在字符映射查找表中指定。 |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | 如果设置，则字符串应垂直渲染。 |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | 如果设置，则字符字形位置应相对于第一个字形的位置进行计算。 |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | 如果设置，则应使用更少的内存来缓存抗锯齿字形，这会导致较低质量的文本渲染。 |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


如果设置，则字符字形的位置应在字符映射查找表中指定。如果未设置，则字形位置应从坐标数组中获取。

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


如果设置，则字符串应垂直渲染。如果未设置，则字符串应水平渲染。

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


如果设置，字符字形位置应相对于第一个字形的位置进行计算。如果清除，字形位置应从坐标数组中获取。

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


如果设置，应使用更少的内存来缓存抗锯齿字形，这会导致较低质量的文本渲染。如果清除，应使用更多的内存，这会产生更高质量的文本渲染。

