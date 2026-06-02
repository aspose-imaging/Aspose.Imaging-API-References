---
title: "类 EmfPlusOffsetClip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusOffsetClip 类。EmfPlusOffsetClip 记录对世界空间的当前裁剪区域应用平移变换。新的当前裁剪区域设置为平移变换的结果。"
type: docs
weight: 6300
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---
## EmfPlusOffsetClip class

此 EmfPlusOffsetClip 记录对当前世界空间的剪裁区域应用平移变换。新的当前剪裁区域被设置为平移变换的结果。

```csharp
public sealed class EmfPlusOffsetClip : EmfPlusClippingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusOffsetClip](emfplusoffsetclip/)(EmfPlusRecord) | 初始化 `EmfPlusOffsetClip` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dx/) { get; set; } | 获取或设置指定平移水平偏移的 32 位浮点值。 |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/dy/) { get; set; } | 获取或设置指定平移垂直偏移的 32 位浮点值。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


