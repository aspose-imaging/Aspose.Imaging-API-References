---
title: "类 EmfRestoreDc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRestoreDc 类。EMR_RESTOREDC 记录将回放设备上下文恢复到指定状态。回放设备上下文通过弹出先前 EMR_SAVEDC 记录（第 2.3.11 节）创建的堆栈中的状态信息来恢复。"
type: docs
weight: 4300
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
## EmfRestoreDc class

该 EMR_RESTOREDC 记录将回放设备上下文恢复到指定状态。回放设备上下文通过弹出先前 EMR_SAVEDC 记录（第 2.3.11 节）创建的堆栈中的状态信息来恢复。

```csharp
public sealed class EmfRestoreDc : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfRestoreDc](emfrestoredc/#constructor)() | 初始化 `EmfRestoreDc` 类的新实例。 |
| [EmfRestoreDc](emfrestoredc/#constructor_1)(EmfRecord) | 初始化 `EmfRestoreDc` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [SavedDc](../../aspose.imaging.fileformats.emf.emf.records/emfrestoredc/saveddc/) { get; set; } | 获取或设置一个 32 位有符号整数，指定相对于当前状态要恢复的已保存状态。此值必须为负；–1 表示最近一次保存在堆栈上的状态，–2 表示其之前的状态，依此类推。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

该栈可以包含多个回放设备上下文实例的状态信息。当状态被恢复时，所有较近期保存的状态实例必须被丢弃。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


