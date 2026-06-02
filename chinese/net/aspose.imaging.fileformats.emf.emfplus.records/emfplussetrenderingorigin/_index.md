---
title: "类 EmfPlusSetRenderingOrigin"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetRenderingOrigin 类。EmfPlusSetRenderingOrigin 记录指定图形输出的渲染原点。"
type: docs
weight: 6490
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---
## EmfPlusSetRenderingOrigin class

EmfPlusSetRenderingOrigin 记录指定图形输出的渲染原点。

```csharp
public sealed class EmfPlusSetRenderingOrigin : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetRenderingOrigin](emfplussetrenderingorigin/)(EmfPlusRecord) | 初始化 `EmfPlusSetRenderingOrigin` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |
| [X](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/x/) { get; set; } | 获取或设置一个 32 位无符号整数，定义渲染原点的水平坐标值。 |
| [Y](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/y/) { get; set; } | 获取或设置一个 32 位无符号整数，定义渲染原点的垂直坐标值。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


