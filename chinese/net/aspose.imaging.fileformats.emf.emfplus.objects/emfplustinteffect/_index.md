---
title: "类 EmfPlusTintEffect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTintEffect 类。TintEffect 对象指定向图像中指定色相添加黑色或白色。"
type: docs
weight: 5950
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
## EmfPlusTintEffect class

TintEffect 对象指定在图像中对指定色相添加黑色或白色。

```csharp
public sealed class EmfPlusTintEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusTintEffect](emfplustinteffect/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Amount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/amount/) { get; set; } | 获取或设置 一个 32 位有符号整数，指定色相的增强或削弱程度。-100 ≤ value < 0 负值指定色相被削弱的程度，相当于添加黑色。0 值为 0 表示 tint 不应改变。0 < value ≤ 100 正值指定色相被增强的程度，相当于添加白色。 |
| [Hue](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/hue/) { get; set; } | 获取或设置 一个 32 位有符号整数，指定 tint 效果应用的色相。-180 ≤ value < 0 从蓝色开始逆时针旋转色轮的指定颜色。0 值为 0 表示色轮上的蓝色。0 < value ≤ 180 从蓝色开始顺时针旋转色轮的指定颜色。 |

### 另请参见

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


