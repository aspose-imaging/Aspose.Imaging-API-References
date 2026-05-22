---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | 初始化 EmfPlusColorCurveEffect 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | 获取或设置 一个 32 位有符号整数，指定对由 CurveChannel 指定的颜色通道进行曲线调整的强度。此字段的有意义值范围取决于 CurveAdjustment 的取值，具体如下：<br/>            曝光调整范围：<br/>            -255 ≤ value &lt; 0 当值减小时，图像的曝光应当减小。<br/>            0 值为 0 表示曝光不得改变。<br/>            0 < value ≤ 255 当值增大时，图像的曝光应当增大。<br/>            密度调整范围：<br/>            -255 ≤ value &lt; 0 当值减小时，图像的密度应当减小，导致图像更暗。<br/>            0 值为 0 表示密度不得改变。<br/>            0 < value ≤ 255 当值增大时，图像的密度应当增大。<br/>            对比度调整范围：<br/>            -100 ≤ value &lt; 0 当值减小时，对比度应当减小。<br/>            0 值为 0 表示对比度不得改变。<br/>            0 < value ≤ 100 当值增大时，对比度应当增大。<br/>            高光调整范围：<br/>            -100 ≤ value &lt; 0 当值减小时，图像的亮部应当变暗。<br/>            0 值为 0 表示高光不得改变。<br/>            0 < value ≤ 100 当值增大时，图像的亮部应当变亮。<br/>            阴影调整范围：<br/>            -100 ≤ value &lt; 0 当值减小时，图像的暗部应当变暗。<br/>            0 值为 0 表示阴影不得改变。<br/>            0 < value ≤ 100 当值增大时，图像的暗部应当变亮。<br/>            白色饱和度调整范围：<br/>            0 — 255 当值增大时，颜色通道强度范围的上限增大。<br/>            黑色饱和度调整范围：<br/>            0 — 255 当值增大时，颜色通道强度范围的下限增大。 |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | 获取或设置 一个 32 位无符号整数，指定要应用于位图中颜色的曲线调整。此值必须在 CurveAdjustments 枚举中定义（第 2.1.1.7 节）。 |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | 获取或设置 一个 32 位无符号整数，指定曲线调整所作用的颜色通道。此值必须在 CurveChannel 枚举中定义（第 2.1.1.8 节）。 |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

初始化 EmfPlusColorCurveEffect 类的新实例

