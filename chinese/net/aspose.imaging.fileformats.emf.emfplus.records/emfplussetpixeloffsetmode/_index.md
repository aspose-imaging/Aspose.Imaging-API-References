---
title: "类 EmfPlusSetPixelOffsetMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetPixelOffsetMode 类。EmfPlusSetPixelOffsetMode 记录指定像素相对于绘图表面坐标的居中方式。"
type: docs
weight: 6480
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/
---
## EmfPlusSetPixelOffsetMode class

EmfPlusSetPixelOffsetMode 记录指定像素相对于绘图表面坐标的居中方式。

```csharp
public sealed class EmfPlusSetPixelOffsetMode : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetPixelOffsetMode](emfplussetpixeloffsetmode/)(EmfPlusRecord) | 初始化 `EmfPlusSetPixelOffsetMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PixelOffsetMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/pixeloffsetmode/) { get; set; } | 获取或设置像素偏移模式值，来自 PixelOffsetMode 枚举（第 2.1.1.26 节）。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


