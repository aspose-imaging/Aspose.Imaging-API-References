---
title: "类 EmfSetColorAdjustment"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorAdjustment 类。EMR_SETCOLORADJUSTMENT 记录指定播放设备上下文中的颜色调整属性。"
type: docs
weight: 4430
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

该 EMR_SETCOLORADJUSTMENT 记录在回放设备上下文中指定颜色调整属性。

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment/)(EmfRecord) | 初始化 `EmfSetColorAdjustment` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment/) { get; set; } | 获取或设置一个 ColorAdjustment 对象（第 2.2.2 节），该对象指定颜色调整值。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

颜色调整值用于在 STRETCH_HALFTONE 模式（来自 StretchMode 枚举，第 2.1.32 节）被设置时，调整源位图的输入颜色，以供 EMR_STRETCHBLT 和 EMR_STRETCHDIBITS 记录执行的图形操作使用。此记录指定的 ColorAdjustment 对象必须在需要 ColorAdjustment 对象的图形操作中使用，直至通过另一个 EMR_SETCOLORADJUSTMENT 记录指定不同的 ColorAdjustment 对象，或通过 EMR_DELETEOBJECT 记录将该对象移除。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


