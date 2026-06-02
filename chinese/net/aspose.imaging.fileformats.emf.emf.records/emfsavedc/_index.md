---
title: "类 EmfSaveDc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSaveDc 类。将回放设备上下文的当前状态保存到由之前的 EMR_SAVEDC 记录保存的状态栈中（如果有）。该状态包括图形属性和对象，如当前选中的位图、画刷、调色板、字体、画笔和区域。使用 EMR_RESTOREDC 记录来恢复状态。此 EMF 记录不指定任何参数。"
type: docs
weight: 4330
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
## EmfSaveDc class

将回放设备上下文的当前状态保存到由先前 EMR_SAVEDC 记录（如果有）保存的状态堆栈中。该状态包括图形属性和对象，包括当前选中的位图、刷子、调色板、字体、笔和区域。使用 EMR_RESTOREDC 记录来恢复该状态。此 EMF 记录不指定任何参数。

```csharp
public sealed class EmfSaveDc : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSaveDc](emfsavedc/#constructor)() | 初始化 `EmfSaveDc` 类的新实例。 |
| [EmfSaveDc](emfsavedc/#constructor_1)(EmfRecord) | 初始化 `EmfSaveDc` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

该栈可以包含多个回放设备上下文实例的状态信息。当状态被恢复时，所有较近期保存的状态实例必须被丢弃。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


