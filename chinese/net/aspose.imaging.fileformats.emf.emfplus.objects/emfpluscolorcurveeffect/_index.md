---
title: "类 EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorCurveEffect 类。ColorCurveEffect 对象指定图像颜色曲线的八种调整之一。"
type: docs
weight: 5420
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
## EmfPlusColorCurveEffect class

ColorCurveEffect 对象指定了图像颜色曲线的八种调整之一。

```csharp
public sealed class EmfPlusColorCurveEffect : EmfPlusImageEffectsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusColorCurveEffect](emfpluscolorcurveeffect/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdjustmentIntensity](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity/) { get; set; } | 获取或设置一个 32 位有符号整数，指定对 CurveChannel 指定的颜色通道进行曲线调整的强度。此字段的有意义值范围根据 CurveAdjustment 值而变化，具体如下：曝光调整范围：-255 ≤ value < 0 当值减小时，图像的曝光 SHOULD 减少。0 值为 0 表示曝光 MUST NOT 改变。0 < value ≤ 255 当值增大时，图像的曝光 SHOULD 增加。密度调整范围：-255 ≤ value < 0 当值减小时，图像的密度 SHOULD 减少，导致图像变暗。0 值为 0 表示密度 MUST NOT 改变。0 < value ≤ 255 当值增大时，图像的密度 SHOULD 增加。对比度调整范围：-100 ≤ value < 0 当值减小时，对比度 SHOULD 减少。0 值为 0 表示对比度 MUST NOT 改变。0 < value ≤ 100 当值增大时，对比度 SHOULD 增加。高光调整范围：-100 ≤ value < 0 当值减小时，图像的亮部 SHOULD 变暗。0 值为 0 表示高光 MUST NOT 改变。0 < value ≤ 100 当值增大时，图像的亮部 SHOULD 变亮。阴影调整范围：-100 ≤ value < 0 当值减小时，图像的暗部 SHOULD 变暗。0 值为 0 表示阴影 MUST NOT 改变。0 < value ≤ 100 当值增大时，图像的暗部 SHOULD 变亮。白色饱和度调整范围：0 — 255 当值增大时，颜色通道强度范围的上限增大。黑色饱和度调整范围：0 — 255 当值增大时，颜色通道强度范围的下限增大。 |
| [CurveAdjustment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curveadjustment/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要应用于位图颜色的曲线调整。此值 MUST 在 CurveAdjustments 枚举中定义（第 2.1.1.7 节）。 |
| [CurveChannel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curvechannel/) { get; set; } | 获取或设置一个 32 位无符号整数，指定曲线调整适用的颜色通道。此值 MUST 在 CurveChannel 枚举中定义（第 2.1.1.8 节）。 |

### 另请参见

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


