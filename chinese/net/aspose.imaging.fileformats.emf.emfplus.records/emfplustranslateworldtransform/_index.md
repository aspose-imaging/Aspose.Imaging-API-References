---
title: "类 EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusTranslateWorldTransform 类。EmfPlusTranslateWorldTransform 记录对当前的世界空间变换执行平移。"
type: docs
weight: 6580
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
## EmfPlusTranslateWorldTransform class

EmfPlusTranslateWorldTransform 记录对当前世界空间变换执行平移操作。

```csharp
public sealed class EmfPlusTranslateWorldTransform : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusTranslateWorldTransform](emfplustranslateworldtransform/)(EmfPlusRecord) | 初始化 `EmfPlusTranslateWorldTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dx/) { get; set; } | 获取或设置一个 32 位浮点值，定义水平距离。平移通过从 dx 和 dy 字段构建新的世界变换矩阵来执行。 |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dy/) { get; set; } | 获取或设置一个 32 位浮点值，定义垂直距离值。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/postmultipliedmatrix/) { get; } | 获取一个值，指示是否 [post multiplied matrix]。如果设置，则应后乘变换矩阵；如果未设置，则应前乘。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


