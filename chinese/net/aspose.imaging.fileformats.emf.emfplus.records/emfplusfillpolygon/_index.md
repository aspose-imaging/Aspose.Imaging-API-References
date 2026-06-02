---
title: "类 EmfPlusFillPolygon"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPolygon 类。EmfPlusFillPolygon 记录指定填充多边形的内部。"
type: docs
weight: 6220
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

此 EmfPlusFillPolygon 记录指定填充多边形的内部。

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon/)(EmfPlusRecord) | 初始化 `EmfPlusFillPolygon` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid/) { get; set; } | 获取或设置画笔标识符：一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed/) { get; set; } | 获取或设置指示此实例是否压缩的值。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。 |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative/) { get; set; } | 获取或设置一个值，指示此实例是否为相对的。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata/) { get; set; } | 获取或设置点数据 一个由 Count 点组成的数组，定义多边形的顶点。数组中的前两个点指定多边形的第一条边。每个后续点指定一条新边，其顶点包括该点和前一个点。如果最后一点和第一点不重合，它们指定多边形的最后一条边。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


