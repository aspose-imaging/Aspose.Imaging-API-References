---
title: "类 EmfSetPolyFillMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetPolyFillMode 类。EMR_SETPOLYFILLMODE 记录定义多边形填充模式。"
type: docs
weight: 4580
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

EMR_SETPOLYFILLMODE 记录定义多边形填充模式。

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor)() | 初始化 `EmfSetPolyFillMode` 类的新实例。 |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor_1)(EmfRecord) | 初始化 `EmfSetPolyFillMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定多边形填充模式，该值必须位于 PolygonFillMode（第 2.1.27 节）枚举中。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

一般来说，只有在复杂的、重叠的多边形 MUST 被填充的情况下，这些模式才会有所不同；例如，一个由五条边组成的多边形形成一个中心有五边形的五角星。在此情况下，ALTERNATE 模式 SHOULD 填充多边形内部的每隔一个封闭区域（星形的各个尖点），而 WINDING 模式 SHOULD 填充所有区域（星形的各个尖点以及中心的五边形）。当填充模式为 ALTERNATE 时，每条扫描线在奇数边和偶数边之间的区域 SHOULD 被填充。即第一条边与第二条边之间的区域 SHOULD 被填充，第三条边与第四条边之间的区域亦如此，依此类推。当填充模式为 WINDING 时，任何具有非零 winding 值的区域 SHOULD 被填充。winding 值是指用于绘制多边形的笔绕该区域的次数。多边形每条边的方向是重要的。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


