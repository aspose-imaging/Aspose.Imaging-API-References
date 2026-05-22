---
title: "类 EmfPlusPenData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenData 类。EmfPlusPenData 对象指定图形笔的属性。"
type: docs
weight: 5790
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
## EmfPlusPenData class

该 EmfPlusPenData 对象指定图形笔的属性。

```csharp
public sealed class EmfPlusPenData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPenData](emfpluspendata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/optionaldata/) { get; set; } | 获取或设置可选的 EmfPlusPenOptionalData 对象（章节 2.2.2.34），该对象指定笔对象的附加数据。此字段的具体内容由 PenDataFlags 字段的值决定。 |
| [PenDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/pendataflags/) { get; set; } | 获取或设置 32 位无符号整数，指定 OptionalData 字段中的数据。此值必须由 PenData 标志组成（章节 2.1.2.7）。 |
| [PenUnit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penunit/) { get; set; } | 获取或设置 32 位无符号整数，指定笔的测量单位。该值必须来自 UnitType 枚举（章节 2.1.1.33）。 |
| [PenWidth](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penwidth/) { get; set; } | 获取或设置 32 位浮点值，指定笔绘制的线条宽度，单位由 PenUnit 字段指定。如果指定宽度为零，则使用最小值，该值由单位决定。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


