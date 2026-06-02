---
title: "类 EmfScaleWindowExtex"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleWindowExtex 类。EMR_SCALEWINDOWEXTEX 记录通过使用指定的乘数和除数形成的比例，重新指定回放设备上下文的窗口。"
type: docs
weight: 4350
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
## EmfScaleWindowExtex class

该 EMR_SCALEWINDOWEXTEX 记录通过使用指定的乘数和除数形成的比例重新指定回放设备上下文的窗口。

```csharp
public sealed class EmfScaleWindowExtex : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor)() | 初始化 `EmfScaleWindowExtex` 类的新实例。 |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor_1)(EmfRecord) | 初始化 `EmfScaleWindowExtex` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xdenom/) { get; set; } | 获取或设置一个 32 位有符号整数，指定水平除数。该值不得为零。 |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xnum/) { get; set; } | 获取或设置一个 32 位有符号整数，指定水平乘数。该值不得为零。 |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ydenom/) { get; set; } | 获取或设置一个 32 位有符号整数，指定垂直除数。该值不得为零。 |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ynum/) { get; set; } | 获取或设置一个 32 位有符号整数，指定垂直乘数。该值不得为零。 |

## 备注

如果设备上下文使用固定比例映射模式，则无法更改范围。只有 MM_ISOTROPIC 和 MM_ANISOTROPIC 不是固定比例。窗口范围按如下方式修改：xNewWE = (xOldWE * xNum) / xDenom，yNewWE = (yOldWE * yNum) / yDenom。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


