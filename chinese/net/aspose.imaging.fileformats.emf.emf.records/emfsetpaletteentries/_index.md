---
title: "类 EmfSetPaletteEntries"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetPaletteEntries 类。EMR_SETPALETTEENTRIES 记录为现有的 LogPalette（第 2.2.17 节）对象定义一系列条目的 RGB 颜色值。"
type: docs
weight: 4560
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
## EmfSetPaletteEntries class

EMR_SETPALETTEENTRIES 记录为现有的 LogPalette（第 2.2.17 节）对象的若干条目定义 RGB 颜色值。

```csharp
public sealed class EmfSetPaletteEntries : EmfObjectManipulationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetPaletteEntries](emfsetpaletteentries/)(EmfRecord) | 初始化 `EmfSetPaletteEntries` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32PalEntries](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/argb32palentries/) { get; set; } | 获取或设置一个 LogPaletteEntry（第 2.2.18 节）对象数组，长度为 NumberOfEntries，指定调色板条目数据。Values 成员不包含任何值。 |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/ihpal/) { get; set; } | 获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。 |
| [NumberofEntries](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/numberofentries/) { get; set; } | 获取或设置一个 32 位无符号整数，指定条目数量。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/start/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


