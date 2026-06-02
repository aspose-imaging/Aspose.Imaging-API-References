---
title: "类 EmfSetColorSpace"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorSpace 类。EMR_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象"
type: docs
weight: 4440
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

该 EMR_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象。

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace/)(EmfRecord) | 初始化 `EmfSetColorSpace` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表 (第 3.1.1.1 节) 中逻辑颜色空间对象的索引。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

此记录定义的逻辑颜色空间对象必须在后续 EMF 记录指定的绘图操作中使用，直至另一个 EMR_SETCOLORSPACE 记录指定不同的逻辑颜色空间对象，或该对象被 EMR_DELETECOLORSPACE 记录删除。

### 另请参见

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


