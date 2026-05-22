---
title: "类 EmfScaleViewportExtex"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleViewportExtex 类。EMR_SCALEVIEWPORTEXTEX 记录通过使用指定的乘数和除数形成的比例重新指定设备上下文的视口。"
type: docs
weight: 4340
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
## EmfScaleViewportExtex class

该 EMR_SCALEVIEWPORTEXTEX 记录通过使用指定的乘数和除数形成的比例重新指定设备上下文的视口。

```csharp
public sealed class EmfScaleViewportExtex : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor)() | 初始化 `EmfScaleViewportExtex` 类的新实例。 |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor_1)(EmfRecord) | 初始化 `EmfScaleViewportExtex` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xdenom/) { get; set; } | 获取或设置一个 32 位有符号整数，指定水平除数。不能为零。 |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xnum/) { get; set; } | 获取或设置一个 32 位有符号整数，指定水平乘数。不能为零。 |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ydenom/) { get; set; } | 获取或设置一个 32 位有符号整数，指定垂直除数。不能为零。 |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ynum/) { get; set; } | 获取或设置一个 32 位有符号整数，指定垂直乘数。不能为零。 |

## 备注

如果设备上下文使用固定比例映射模式，则不能更改范围。只有 MM_ISOTROPIC 和 MM_ANISOTROPIC 不是固定比例。视口范围按如下方式修改。xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


