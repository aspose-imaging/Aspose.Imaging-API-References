---
title: "EmfPlusDrawArc.DataSize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusDrawArc 属性。获取或设置数据的大小。一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。对于此记录类型，该值必须是以下之一：0x00000010（如果 Flags 字段中的 C 位被设置）；0x00000018（如果 C 位未设置）。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize/
---
## EmfPlusDrawArc.DataSize property

获取或设置数据的大小。一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。对于此记录类型，值必须是以下之一：0x00000010（如果 Flags 字段中的 C 位被设置）。0x00000018（如果 Flags 字段中的 C 位被清除）。

```csharp
public override int DataSize { get; set; }
```

### Property Value

数据的大小。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidDataException | 无效的值 |

### 另请参见

* class [EmfPlusDrawArc](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawarc/)
* assembly [Aspose.Imaging](../../../)


