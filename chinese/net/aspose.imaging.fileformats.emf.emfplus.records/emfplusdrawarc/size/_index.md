---
title: "EmfPlusDrawArc.Size"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusDrawArc 属性。获取或设置大小。一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，该值必须是以下之一：0x0000001C（如果 Flags 字段中的 C 位被设置）；0x00000024（如果 C 位未设置）。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/size/
---
## EmfPlusDrawArc.Size property

获取或设置大小。一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，值必须是以下之一：0x0000001C（如果 Flags 字段中的 C 位被设置）。0x00000024（如果 Flags 字段中的 C 位被清除）。

```csharp
public override int Size { get; set; }
```

### Property Value

大小。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidDataException | 无效的值 |

### 另请参见

* class [EmfPlusDrawArc](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawarc/)
* assembly [Aspose.Imaging](../../../)


