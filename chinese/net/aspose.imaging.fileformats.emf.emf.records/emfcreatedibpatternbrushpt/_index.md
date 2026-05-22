---
title: "类 EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateDibPatternBrushPt 类。EMR_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案刷。该图案由 DIB 指定"
type: docs
weight: 3590
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
## EmfCreateDibPatternBrushPt class

EMR_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案画刷。该图案由 DIB 指定。

```csharp
public sealed class EmfCreateDibPatternBrushPt : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor)() | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |
| [EmfCreateDibPatternBrushPt](emfcreatedibpatternbrushpt/#constructor_1)(EmfRecord) | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/bitmapbuffer/) { get; set; } | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR_CREATEDIBPATTERNBRUSHPT 记录的固定部分连续。 |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/ihbrush/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表 (第 3.1.1.1 节) 中图案刷对象的索引。必须保存此索引，以便可以重新使用或修改该对象。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/usage/) { get; set; } | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 头部颜色表中的值。此值必须属于 DIBColors 枚举（第 2.1.9 节）。 |

## 备注

此记录定义的图案刷对象可以通过 EMR_SELECTOBJECT 记录（第 2.3.8.5 节）选择到回放设备上下文中，该记录指定后续图形操作中使用的图案刷。

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


