---
title: "类 EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusScaleWorldTransform 类。EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。"
type: docs
weight: 6380
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
## EmfPlusScaleWorldTransform class

此 EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。

```csharp
public sealed class EmfPlusScaleWorldTransform : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusScaleWorldTransform](emfplusscaleworldtransform/)(EmfPlusRecord) | 初始化 `EmfPlusScaleWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/postmultipliedmatrix/) { get; } | 获取一个值，指示 [post multiplied matrix]。如果设置，则变换矩阵应后乘。如果未设置，则应前乘。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Sx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sx/) { get; set; } | 获取或设置定义水平缩放因子的 32 位浮点值。缩放通过从 Sx 和 Sy 字段值构建新的变换矩阵来执行，如下表所示。 ----------------- &#x7C; Sx &#x7C; 0 &#x7C; 0 &#x7C; &#x7C; 0 &#x7C; Sx &#x7C; 0 &#x7C; ----------------- 图 3：缩放变换矩阵 |
| [Sy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sy/) { get; set; } | 获取或设置定义垂直缩放因子的 32 位浮点值。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


