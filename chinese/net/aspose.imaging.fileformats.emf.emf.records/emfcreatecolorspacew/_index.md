---
title: "类 EmfCreateColorSpaceW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateColorSpaceW 类。EMR_CREATECOLORSPACEW 记录从具有 Unicode 字符名称的颜色配置文件创建逻辑颜色空间对象。"
type: docs
weight: 3580
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
## EmfCreateColorSpaceW class

EMR_CREATECOLORSPACEW 记录从名称由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象。

```csharp
public sealed class EmfCreateColorSpaceW : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCreateColorSpaceW](emfcreatecolorspacew/)(EmfRecord) | 初始化 `EmfCreateColorSpaceW` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/cbdata/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（字节）。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/data/) { get; set; } | 获取或设置一个可选的字节数组，用于指定颜色配置文件数据。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/dwflags/) { get; set; } | 获取或设置一个 32 位无符号整数，提供有关此记录中数据的信息。 |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/ihcs/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。必须保存此索引，以便该对象可以被重用或修改。 |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/lcs/) { get; set; } | 获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），该对象可以使用 Unicode UTF16-LE 字符指定颜色配置文件的名称。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

此记录定义的逻辑颜色空间对象可以通过 EMR_SETCOLORSPACE 记录（第 2.3.8.7 节）选入播放设备上下文，该记录定义后续图形操作中使用的逻辑颜色空间。

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


