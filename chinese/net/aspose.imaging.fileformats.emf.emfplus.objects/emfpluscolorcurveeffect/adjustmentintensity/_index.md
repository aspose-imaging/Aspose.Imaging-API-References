---
title: "EmfPlusColorCurveEffect.AdjustmentIntensity"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusColorCurveEffect 属性。获取或设置一个 32 位有符号整数，指定对 CurveChannel 指定的颜色通道进行曲线调整的强度。此字段的有意义值范围根据 CurveAdjustment 值而变化，如下所示：曝光调整范围 255 值 0 当值减小时，图像的曝光应降低。0 值为 0 表示曝光必须不变。0 值 255 当值增加时，图像的曝光应增加。密度调整范围 255 值 0 当值减小时，图像的密度应降低，导致图像更暗。0 值为 0 表示密度必须不变。0 值 255 当值增加时，图像的密度应增加。对比度调整范围 100 值 0 当值减小时，图像的对比度应降低。0 值为 0 表示对比度必须不变。0 值 100 当值增加时，图像的对比度应增加。高光调整范围 100 值 0 当值减小时，图像的亮部应显得更暗。0 值为 0 表示高光必须不变。0 值 100 当值增加时，图像的亮部应显得更亮。阴影调整范围 100 值 0 当值减小时，图像的暗部应显得更暗。0 值为 0 表示阴影必须不变。0 值 100 当值增加时，图像的暗部应显得更亮。白色饱和度调整范围 0‑255 当值增加时，颜色通道强度范围的上限增加。黑色饱和度调整范围 0‑255 当值增加时，颜色通道强度范围的下限增加"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity/
---
## EmfPlusColorCurveEffect.AdjustmentIntensity property

获取或设置一个 32 位有符号整数，指定对 CurveChannel 指定的颜色通道进行曲线调整的强度。此字段的有意义值范围根据 CurveAdjustment 值而变化，具体如下：曝光调整范围：-255 ≤ value < 0 当值减小时，图像的曝光 SHOULD 减少。0 值为 0 表示曝光 MUST NOT 改变。0 < value ≤ 255 当值增大时，图像的曝光 SHOULD 增加。密度调整范围：-255 ≤ value < 0 当值减小时，图像的密度 SHOULD 减少，导致图像变暗。0 值为 0 表示密度 MUST NOT 改变。0 < value ≤ 255 当值增大时，图像的密度 SHOULD 增加。对比度调整范围：-100 ≤ value < 0 当值减小时，对比度 SHOULD 减少。0 值为 0 表示对比度 MUST NOT 改变。0 < value ≤ 100 当值增大时，对比度 SHOULD 增加。高光调整范围：-100 ≤ value < 0 当值减小时，图像的亮部 SHOULD 变暗。0 值为 0 表示高光 MUST NOT 改变。0 < value ≤ 100 当值增大时，图像的亮部 SHOULD 变亮。阴影调整范围：-100 ≤ value < 0 当值减小时，图像的暗部 SHOULD 变暗。0 值为 0 表示阴影 MUST NOT 改变。0 < value ≤ 100 当值增大时，图像的暗部 SHOULD 变亮。白色饱和度调整范围：0 — 255 当值增大时，颜色通道强度范围的上限增大。黑色饱和度调整范围：0 — 255 当值增大时，颜色通道强度范围的下限增大。

```csharp
public int AdjustmentIntensity { get; set; }
```

### 另请参见

* class [EmfPlusColorCurveEffect](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscolorcurveeffect/)
* assembly [Aspose.Imaging](../../../)


