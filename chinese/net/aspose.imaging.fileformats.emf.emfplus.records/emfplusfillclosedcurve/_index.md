---
title: "类 EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillClosedCurve 类。EmfPlusFillClosedCurve 记录指定填充闭合基数样条的内部。"
type: docs
weight: 6180
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

EmfPlusFillClosedCurve 记录指定填充闭合的基数样条曲线内部。

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve/)(EmfPlusRecord) | 初始化 `EmfPlusFillClosedCurve` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid/) { get; set; } | 获取或设置画笔标识符。一个 32 位无符号整数，指定 EmfPlusBrush，其内容由 Flags 字段中的 S 位决定。此画笔用于填充闭合基数样条的内部。 |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。 ---------------------- "环绕" 填充操作根据 "奇偶校验" 规则填充区域。根据该规则，测试点是否位于闭合曲线内部的判定方法如下：从测试点向远离曲线的点绘制一条直线。如果该直线与曲线相交的次数为奇数，则测试点在曲线内部；否则在曲线外部。 --------------------- "交替" 填充操作根据 "非零" 规则填充区域。根据该规则，测试点是否位于闭合曲线内部的判定方法如下：从测试点向远离曲线的点绘制一条直线。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，则测试点在曲线外部；否则在曲线内部。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata/) { get; set; } | 获取或设置点数据。一个包含 Count 个点的数组，指定定义样条的线段的端点。在闭合基数样条中，曲线会通过 PointData 数组中的最后一个点并连接到数组中的第一个点。 |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，则上面的 C 标志未定义，必须被忽略。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension/) { get; set; } | 获取或设置张力。一个 32 位浮点值，指定样条通过各点时的弯曲程度。值为 0.0 表示样条是一系列直线。值越大，曲线越圆滑。更多信息请参见 [SPLINE77] 和 [PETZOLD]。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusFillClosedCurve` 是否为环绕填充。此位指示填充操作的方式。如果设置，则填充为 "环绕" 填充；如果未设置，则填充为 "交替" 填充。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


