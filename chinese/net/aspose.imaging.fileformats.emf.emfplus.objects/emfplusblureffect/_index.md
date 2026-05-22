---
title: "类 EmfPlusBlurEffect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlurEffect 类。BlurEffect 对象指定图像中像素强度差异的降低"
type: docs
weight: 5340
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
## EmfPlusBlurEffect class

BlurEffect 对象指定了图像中像素强度差异的降低。

```csharp
public sealed class EmfPlusBlurEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBlurEffect](emfplusblureffect/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlurRadius](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/blurradius/) { get; set; } | 获取或设置一个 32 位浮点数，指定以像素为单位的模糊半径，该半径决定计算给定像素新值时涉及的像素数量。此值必须在 0.0 到 255.0 范围内。 |
| [ExpandEdge](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/expandedge/) { get; set; } | 获取或设置一个 32 位布尔值，指定位图是否按等于 BlurRadius 值的量扩展以产生柔和边缘。此值必须是以下之一：FALSE 0x00000000 位图的大小不得改变，其柔和边缘应被裁剪至 BlurRadius 的大小。TRUE 0x00000001 位图的大小应按等于 BlurRadius 的量扩展以产生柔和边缘。 |

### 另请参见

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


