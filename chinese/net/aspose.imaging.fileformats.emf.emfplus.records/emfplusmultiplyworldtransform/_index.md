---
title: "类 EmfPlusMultiplyWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusMultiplyWorldTransform 类。EmfPlusMultiplyWorldTransform 记录通过指定的变换矩阵乘以当前的世界空间变换。"
type: docs
weight: 6270
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
## EmfPlusMultiplyWorldTransform class

此 EmfPlusMultiplyWorldTransform 记录将当前世界空间变换乘以指定的变换矩阵。

```csharp
public sealed class EmfPlusMultiplyWorldTransform : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusMultiplyWorldTransform](emfplusmultiplyworldtransform/)(EmfPlusRecord) | 初始化 `EmfPlusMultiplyWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/matrixdata/) { get; set; } | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象定义乘法矩阵。 |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/postmultipliedmatrix/) { get; } | 获取一个值，指示 [post multiplied matrix]。如果设置，则变换矩阵应后乘。如果未设置，则应前乘。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


