---
title: "类 EmfSetTextJustification"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextJustification 类。EMR_SETTEXTJUSTIFICATION 记录指定为文本对齐在断字符处添加的额外空间量。"
type: docs
weight: 4630
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
## EmfSetTextJustification class

EMR_SETTEXTJUSTIFICATION 记录指定为文本两端对齐在换行字符处添加的额外空间量。

```csharp
public sealed class EmfSetTextJustification : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetTextJustification](emfsettextjustification/)(EmfRecord) | 初始化 `EmfSetTextJustification` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [NBreakCount](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakcount/) { get; set; } | 获取或设置一个 32 位有符号整数，指定断字符的数量。 |
| [NBreakExtra](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakextra/) { get; set; } | 获取或设置一个 32 位有符号整数，指定要添加的总额外空间（以逻辑单位计）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

实现不应使用 EMR_SETTEXTJUSTIFICATION 记录，而应使用 EMR_EXTTEXTOUTW 记录（第 2.3.5.8 节）来执行此功能。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


