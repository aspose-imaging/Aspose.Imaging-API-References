---
title: "枚举 EmfPlusDriverStringOptionsFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusDriverStringOptionsFlags 枚举。DriverStringOptions 标志指定图形文本定位和渲染的属性。这些标志可以组合以指定多个选项。"
type: docs
weight: 4910
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
## EmfPlusDriverStringOptionsFlags enumeration

DriverStringOptions 标志指定图形文本定位和渲染的属性。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum EmfPlusDriverStringOptionsFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| DriverStringOptionsCmapLookup | `1` | 如果设置，则字符字形的位置应在字符映射查找表中指定。如果未设置，则字形位置应从坐标数组中获取。 |
| DriverStringOptionsVertical | `2` | 如果设置，则字符串应垂直渲染。如果未设置，则字符串应水平渲染。 |
| DriverStringOptionsRealizedAdvance | `4` | 如果设置，则字符字形位置应相对于第一个字形的位置计算。如果未设置，则字形位置应从坐标数组中获取。 |
| DriverStringOptionsLimitSubpixel | `8` | 如果设置，则应使用更少的内存来缓存抗锯齿字形，这会导致较低质量的文本渲染。如果未设置，则应使用更多的内存，这会产生更高质量的文本渲染。 |

## 备注

图形文本输出在 [`EmfPlusDrawDriverString`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) 记录中指定。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


