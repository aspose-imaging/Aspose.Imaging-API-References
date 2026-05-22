---
title: "类 EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusRotateWorldTransform 类。EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。"
type: docs
weight: 6360
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
## EmfPlusRotateWorldTransform class

此 EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。

```csharp
public sealed class EmfPlusRotateWorldTransform : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusRotateWorldTransform](emfplusrotateworldtransform/)(EmfPlusRecord) | 初始化 `EmfPlusRotateWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/) { get; set; } | 获取或设置一个 32 位浮点值，指定以度为单位的旋转角度。该操作通过从以下图表构建新的变换矩阵来执行： --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- 图 2：旋转变换矩阵 当前的世界空间变换会与此矩阵相乘，结果成为新的当前世界空间变换。Flags 字段决定乘法的顺序。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/postmultipliedmatrix/) { get; } | 获取一个值，指示是否 [post multiplied matrix]。如果设置，则应后乘变换矩阵；如果未设置，则应前乘。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


