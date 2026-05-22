---
title: "类 EmfResizePalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfResizePalette 类。EMR_RESIZEPALETTE 记录增加或减少现有 LogPalette 对象的大小（第 2.2.17 节）。"
type: docs
weight: 4290
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
## EmfResizePalette class

该 EMR_RESIZEPALETTE 记录增大或减小现有 LogPalette 对象（第 2.2.17 节）的大小。

```csharp
public sealed class EmfResizePalette : EmfObjectManipulationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfResizePalette](emfresizepalette/)(EmfRecord) | 初始化 `EmfResizePalette` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfresizepalette/ihpal/) { get; set; } | 获取或设置一个 32 位无符号整数，指定调色板对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

LogPalette 对象的新大小必须反映在该结构中的 NumberOfEntries 字段中。

### 另请参见

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


