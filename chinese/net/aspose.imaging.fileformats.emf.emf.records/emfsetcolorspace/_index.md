---
title: EmfSetColorSpace
second_title: Aspose.Imaging for .NET API 参考
description: EMR_SETCOLORSPACE 记录定义了图形操作的当前逻辑色彩空间对象
type: docs
weight: 4320
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

EMR_SETCOLORSPACE 记录定义了图形操作的当前逻辑色彩空间对象。

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace)(EmfRecord) | 初始化[`EmfSetColorSpace`](../emfsetcolorspace)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs) { get; set; } | 获取或设置一个 32 位无符号整数，该整数指定 EMF 对象表中逻辑色彩空间对象 的索引（第 3.1 节。 1.1）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

此记录定义的逻辑色彩空间对象必须在以下绘图操作中使用 由后续 EMF 记录指定，直到 另一个 EMR_SETCOLORSPACE 记录指定不同的逻辑色彩空间对象，或者该对象被 EMR_DELETECOLORSPACE 记录删除。

### 也可以看看

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
