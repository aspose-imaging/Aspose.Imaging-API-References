---
title: "类 EmfCreateMonoBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateMonoBrush 类。EMR_CREATEMONOBRUSH 记录为图形操作定义单色图案画刷。该图案由单色 DIB 指定。"
type: docs
weight: 3600
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
## EmfCreateMonoBrush class

EMR_CREATEMONOBRUSH 记录定义用于图形操作的单色图案画刷。该图案由单色 DIB 指定。

```csharp
public sealed class EmfCreateMonoBrush : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCreateMonoBrush](emfcreatemonobrush/)(EmfRecord) | 初始化 `EmfCreateMonoBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/bitmapbuffer/) { get; set; } | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR_CREATEDIBPATTERNBRUSHPT 记录的固定部分连续。 |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/ihbrush/) { get; set; } | 获取或设置一个 32 位无符号整数，指定单色图案画刷对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便可以重新使用或修改该对象。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/usage/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 头部颜色表中的值。此值必须属于 DIBColors 枚举（第 2.1.9 节）。 |

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


