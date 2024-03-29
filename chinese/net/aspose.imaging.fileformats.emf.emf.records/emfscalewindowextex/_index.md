---
title: EmfScaleWindowExtex
second_title: Aspose.Imaging for .NET API 参考
description: EMR_SCALEWINDOWEXTEX 记录通过 使用由指定的被乘数和除数形成的比率重新指定播放设备上下文的窗口
type: docs
weight: 4230
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
## EmfScaleWindowExtex class

EMR_SCALEWINDOWEXTEX 记录通过 使用由指定的被乘数和除数形成的比率重新指定播放设备上下文的窗口。

```csharp
public sealed class EmfScaleWindowExtex : EmfStateRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfScaleWindowExtex](emfscalewindowextex#constructor)() | 初始化[`EmfScaleWindowExtex`](../emfscalewindowextex)类. |
| [EmfScaleWindowExtex](emfscalewindowextex#constructor_1)(EmfRecord) | 初始化[`EmfScaleWindowExtex`](../emfscalewindowextex)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xdenom) { get; set; } | 获取或设置指定水平除数的 32 位有符号整数。不得为零。 |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xnum) { get; set; } | 获取或设置指定水平被乘数的 32 位有符号整数。不得为零。 |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ydenom) { get; set; } | 获取或设置一个指定垂直除数的 32 位有符号整数。不得为零。 |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ynum) { get; set; } | 获取或设置指定垂直被乘数的 32 位有符号整数。不得为零。 |

### 评论

如果设备上下文使用固定比例映射模式，则无法更改范围。只有 MM_ISOTROPIC 和MM_ANISOTROPIC 不是固定比例。窗口范围为 修改如下。 xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### 也可以看看

* class [EmfStateRecordType](../emfstaterecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
