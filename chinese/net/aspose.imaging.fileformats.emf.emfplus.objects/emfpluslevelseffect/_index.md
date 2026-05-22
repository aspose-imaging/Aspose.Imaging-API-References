---
title: "类 EmfPlusLevelsEffect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLevelsEffect 类。LevelsEffect 对象指定图像的高光、中间调和阴影的调整。"
type: docs
weight: 5660
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
## EmfPlusLevelsEffect class

LevelsEffect 对象指定对图像的高光、中间调和阴影的调整。

```csharp
public sealed class EmfPlusLevelsEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusLevelsEffect](emfpluslevelseffect/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Highlight](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/highlight/) { get; set; } | 获取或设置，指定对图像高光的提亮程度。强度范围高端的颜色通道值比中间或低端的值变化更大，这意味着可以在不失去图像暗部对比度的情况下提亮图像。0 ≤ value < 指定强度百分比高于此阈值的高光 SHOULD 增加。100 指定高光 MUST NOT 改变。 |
| [MidTone](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/midtone/) { get; set; } | 获取或设置，指定对图像中间调的提亮或加暗程度。强度范围中部的颜色通道值比高端或低端的值变化更大，这意味着可以在不失去图像最暗和最亮部分对比度的情况下对图像进行提亮或加暗。-100 ≤ value < 0 指定中间调被加暗。0 指定中间调 MUST NOT 改变。0 < value ≤ 100 指定中间调被提亮。 |
| [Shadow](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/shadow/) { get; set; } | 获取或设置，指定对图像阴影的加暗程度。强度范围低端的颜色通道值比中间或高端的值变化更大，这意味着可以在不失去图像亮部对比度的情况下加暗图像。0 指定阴影 MUST NOT 改变。0 < value ≤ 100 指定强度百分比低于此阈值的阴影被加暗。 |

### 另请参见

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


