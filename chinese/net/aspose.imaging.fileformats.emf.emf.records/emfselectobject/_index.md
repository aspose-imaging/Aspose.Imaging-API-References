---
title: "类 EmfSelectObject"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject 类。EMR_SELECTOBJECT 记录向当前元文件回放设备上下文添加图形对象。该对象可以通过其在 EMF 对象表（第 3.1.1.1 节）中的索引或通过其在 StockObject 枚举（第 2.1.31 节）中的值来指定。"
type: docs
weight: 4370
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
## EmfSelectObject class

该 EMR_SELECTOBJECT 记录向当前元文件回放设备上下文添加一个图形对象。该对象可以通过其在 EMF 对象表（第 3.1.1.1 节）中的索引或通过其在 StockObject 枚举（第 2.1.31 节）中的值来指定。

```csharp
public sealed class EmfSelectObject : EmfRecord
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSelectObject](emfselectobject/#constructor)() | 初始化 `EmfSelectObject` 类的新实例。 |
| [EmfSelectObject](emfselectobject/#constructor_1)(EmfRecord) | 初始化 `EmfSelectObject` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ObjectHandle](../../aspose.imaging.fileformats.emf.emf.records/emfselectobject/objecthandle/) { get; set; } | 获取或设置 32 位无符号整数，指定 EMF 对象表中图形对象的索引或来自 [`EmfStockObject`](../../aspose.imaging.fileformats.emf.emf.consts/emfstockobject/) 枚举的库存对象索引。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


