---
title: "类 EmfPlusSetPageTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetPageTransform 类。EmfPlusSetPageTransform 记录指定用于将页面空间坐标转换为设备空间坐标的缩放因子和单位。"
type: docs
weight: 6470
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

EmfPlusSetPageTransform 记录指定用于将页面空间坐标转换为设备空间坐标的缩放因子和单位。

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform/)(EmfPlusRecord) | 初始化 `EmfPlusSetPageTransform` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale/) { get; set; } | 获取或设置一个 32 位浮点值，指定将页面空间坐标转换为设备空间坐标的比例因子。 |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit/) { get; } | 获取页面空间坐标的计量单位，来自 UnitType 枚举（第 2.1.1.33 节）。此值不应为 UnitTypeDisplay 或 UnitTypeWorld。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


