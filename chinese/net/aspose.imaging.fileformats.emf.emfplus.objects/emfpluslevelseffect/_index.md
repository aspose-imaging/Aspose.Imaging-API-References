---
title: EmfPlusLevelsEffect
second_title: Aspose.Imaging for .NET API 参考
description: LevelsEffect 对象指定对图像的高光中间色调和阴影的调整
type: docs
weight: 5540
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
## EmfPlusLevelsEffect class

LevelsEffect 对象指定对图像的高光、中间色调和阴影的调整。

```csharp
public sealed class EmfPlusLevelsEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusLevelsEffect](emfpluslevelseffect)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Highlight](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/highlight) { get; set; } | 获取或设置 指定使图像的高光变亮的程度。强度范围高端的颜色 通道值的变化大于接近 中端或低端的值，这意味着可以在不损失对比度的情况下点亮图像 在图像的较暗部分之间。 0 ≤ 值 &lt;指定强度百分比高于此阈值的高光应该增加 100。 100 指定高亮不能改变。 |
| [MidTone](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/midtone) { get; set; } | 获取或设置 指定图像中间调变亮或变暗的程度。颜色 强度范围中间的通道值比高 或低端附近的值更改得更多，这意味着可以在不损失对比度的情况下使图像变亮或变暗 在图像最暗和最亮的部分之间。 -100 ≤ 值 &lt; 0 指定中间调变暗。 0 指定中间色调不能改变。 0 &lt; value ≤ 100 指定中间调变浅。 |
| [Shadow](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/shadow) { get; set; } | 获取或设置图像阴影的暗度。颜色通道 强度范围低端的值比中间或 高端附近的值变化更大，这意味着图像可以变暗而不会失去两者之间的对比度 图像较亮的部分。 0 指定阴影不能改变。 0 &lt; value ≤ 100 指定强度百分比低于此阈值的阴影将变为 更暗。 |

### 也可以看看

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
