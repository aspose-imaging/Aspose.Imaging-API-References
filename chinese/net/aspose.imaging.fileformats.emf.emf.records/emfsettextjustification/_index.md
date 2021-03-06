---
title: EmfSetTextJustification
second_title: Aspose.Imaging for .NET API 参考
description: EMR_SETTEXTJUSTIFICATION 记录指定要添加到 break 字符以进行文本对齐的额外空间量
type: docs
weight: 4510
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
## EmfSetTextJustification class

EMR_SETTEXTJUSTIFICATION 记录指定要添加到 break 字符以进行文本对齐的额外空间量。

```csharp
public sealed class EmfSetTextJustification : EmfStateRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfSetTextJustification](emfsettextjustification)(EmfRecord) | 初始化[`EmfSetTextJustification`](../emfsettextjustification)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [NBreakCount](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakcount) { get; set; } | 获取或设置一个 32 位有符号整数，用于指定中断字符的数量。 |
| [NBreakExtra](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakextra) { get; set; } | 获取或设置一个 32 位有符号整数，该整数指定要添加的额外空间总量 以逻辑单位表示。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

实现应该使用 EMR_EXTTEXTOUTW 而不是使用 EMR_SETTEXTJUSTIFICATION 记录记录（第 2.3.5.8 节）以执行此功能。

### 也可以看看

* class [EmfStateRecordType](../emfstaterecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
