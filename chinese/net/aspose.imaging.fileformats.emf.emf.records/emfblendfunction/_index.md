---
title: "结构体 EmfBlendFunction"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunction 结构体。该结构体指定源位图和目标位图的混合操作"
type: docs
weight: 3360
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
## EmfBlendFunction structure

指定源位图和目标位图混合操作的结构体。

```csharp
public struct EmfBlendFunction
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfBlendFunction](emfblendfunction/)(int) | 初始化 `EmfBlendFunction` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlphaFormat](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/alphaformat/) { get; } | 获取一个结构体，指定源像素和目标像素在 alpha 透明度方面的解释方式。 |
| [BlendFlags](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendflags/) { get; } | 获取混合标志。此值必须为 0x00，且必须被忽略。 |
| [BlendOperation](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendoperation/) { get; } | 获取混合操作码。唯一已定义的源和目标混合操作是 0x00，它指定源位图必须根据源像素的 alpha 透明度值与目标位图合并。详情请参见下列公式。 |
| [SrcConstantAlpha](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/srcconstantalpha/) { get; } | 获取一个 8 位无符号整数，指定 alpha 透明度，该透明度决定源位图和目标位图的混合方式。此值必须用于整个源位图。最小的 alpha 透明度值 0 表示完全透明，最大值 0xFF 表示完全不透明。实际上，0xFF 表示逐像素的 alpha 值决定源位图和目标位图的混合。详情请参见本节后面的公式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ToInt](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/toint/)() | 将数字的字符串表示转换为整数。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [AlphaFormatEnum](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum) | 一种结构，指定源像素和目标像素相对于 alpha 透明度的解释方式。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


