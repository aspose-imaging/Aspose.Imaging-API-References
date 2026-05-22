---
title: "类 EmfSetTextAlign"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextAlign 类。EMR_SETTEXTALIGN 记录指定文本对齐方式。"
type: docs
weight: 4610
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
## EmfSetTextAlign class

EMR_SETTEXTALIGN 记录指定文本对齐方式。

```csharp
public sealed class EmfSetTextAlign : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetTextAlign](emfsettextalign/#constructor)() | 初始化 `EmfSetTextAlign` 类的新实例。 |
| [EmfSetTextAlign](emfsettextalign/#constructor_1)(EmfRecord) | 初始化 `EmfSetTextAlign` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [TextAlignmentMode](../../aspose.imaging.fileformats.emf.emf.records/emfsettextalign/textalignmentmode/) { get; set; } | 获取或设置一个 32 位无符号整数，通过使用文本对齐标志的掩码来指定文本对齐方式。这些标志可以是 [`WmfTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)（[MS-WMF] 第 2.1.2.3 节），用于水平基线的文本，或 [`WmfVerticalTextAlignmentModeFlags`](../../aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)（[MS-WMF] 第 2.1.2.4 节），用于垂直基线的文本。只能从影响水平和垂直对齐的选项中选择一个值。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

EMR_SMALLTEXTOUT、EMR_EXTTEXTOUTA 和 EMR_EXTTEXTOUTW 记录使用文本对齐值来定位输出介质上的文本字符串。这些值指定参考点与包围文本的矩形之间的关系。参考点可以是当前位置信息或传递给文本输出记录的点。包围文本的矩形由文本字符串中的字符单元构成。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


