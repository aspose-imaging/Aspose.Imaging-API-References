---
title: "类 EmfDeleteColorSpace"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteColorSpace 类。EMR_DELETECOLORSPACE 记录删除逻辑颜色空间对象"
type: docs
weight: 3630
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
## EmfDeleteColorSpace class

EMR_DELETECOLORSPACE 记录删除逻辑颜色空间对象。

```csharp
public sealed class EmfDeleteColorSpace : EmfObjectManipulationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfDeleteColorSpace](emfdeletecolorspace/)(EmfRecord) | 初始化 `EmfDeleteColorSpace` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/ihcs/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表 (第 3.1.1.1 节) 中逻辑颜色空间对象的索引。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

应使用 EMR_DELETEOBJECT 记录而不是 EMR_DELETECOLORSPACE 来删除逻辑颜色空间对象。

### 另请参见

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


