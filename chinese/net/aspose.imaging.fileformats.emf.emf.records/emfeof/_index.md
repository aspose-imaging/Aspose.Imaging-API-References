---
title: "类 EmfEof"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfEof 类。EMR_EOF 记录指示元文件的结束并指定调色板。"
type: docs
weight: 3690
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---
## EmfEof class

EMR_EOF 记录指示元文件的结束并指定调色板。

```csharp
public sealed class EmfEof : EmfControlRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfEof](emfeof/#constructor)() | 初始化 `EmfEof` 类的新实例。 |
| [EmfEof](emfeof/#constructor_1)(EmfRecord) | 初始化 `EmfEof` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PaletteArgb32Entries](../../aspose.imaging.fileformats.emf.emf.records/emfeof/paletteargb32entries/) { get; set; } | 获取或设置一个可选缓冲区，其中包含调色板数据，该缓冲区不需要与 EMR_EOF 记录的固定部分连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。此字段的大小必须是 4 字节的倍数。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [SizeLast](../../aspose.imaging.fileformats.emf.emf.records/emfeof/sizelast/) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录（因此也是元文件）的最后一个字段。如果存在 LogPaletteEntry 对象，则它们必须位于此字段之前。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfControlRecordType](../emfcontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


