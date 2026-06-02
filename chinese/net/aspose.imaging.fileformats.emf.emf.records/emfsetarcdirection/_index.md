---
title: "类 EmfSetArcDirection"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetArcDirection 类。EMR_SETARCDIRECTION 记录指定用于弧和矩形输出的绘制方向。"
type: docs
weight: 4390
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
## EmfSetArcDirection class

该 EMR_SETARCDIRECTION 记录指定用于弧线和矩形输出的绘制方向。

```csharp
public sealed class EmfSetArcDirection : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetArcDirection](emfsetarcdirection/#constructor)() | 初始化 `EmfSetArcDirection` 类的新实例。 |
| [EmfSetArcDirection](emfsetarcdirection/#constructor_1)(EmfRecord) | 初始化 `EmfSetArcDirection` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArcDirection](../../aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/arcdirection/) { get; set; } | 获取或设置一个 32 位无符号整数，指定弧的方向。该值必须属于 ArcDirection 枚举（第 2.1.2 节）。默认方向为逆时针。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

EMR_SETARCDIRECTION 记录影响以下记录的绘制方向：- EMR_ARC（第 2.3.5.2 节） - EMR_ARCTO（第 2.3.5.3 节） - EMR_CHORD（第 2.3.5.4 节） - EMR_ELLIPSE（第 2.3.5.5 节） - EMR_PIE（第 2.3.5.15 节） - EMR_RECTANGLE（第 2.3.5.34 节） - EMR_ROUNDRECT（第 2.3.5.35 节）

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


