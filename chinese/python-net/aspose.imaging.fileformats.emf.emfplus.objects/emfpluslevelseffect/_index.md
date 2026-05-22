---
title: "EmfPlusLevelsEffect 类"
type: docs
weight: 420
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | 初始化 EmfPlusLevelsEffect 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 高亮 | int | r/w | 获取或设置 指定要将图像的高光提亮多少。颜色<br/>            通道值在强度范围的高端的改变程度大于接近中部或低端的值，这意味着可以在不失去图像中较暗部分对比度的情况下提亮图像。<br/>            0 ≤ value &lt; 指定高于此阈值的高光强度百分比应当<br/>            100 被增加。<br/>            100 指定高光不得改变。 |
| mid_tone | int | r/w | 获取或设置 指定要将图像的中间调提亮或加暗多少。强度范围中部的颜色<br/>            通道值的改变程度大于接近高端或低端的值，这意味着可以在不失去图像中最暗和最亮部分对比度的情况下提亮或加暗图像。<br/>            -100 ≤ value &lt; 0 指定中间调被加暗。<br/>            0 指定中间调不得改变。<br/>            0 < value ≤ 100 指定中间调被提亮。 |
| shadow | int | r/w | 获取或设置 指定要将图像的阴影加暗多少。强度范围低端的颜色<br/>            通道值的改变程度大于接近中部或高端的值，这意味着可以在不失去图像中较亮部分对比度的情况下加暗图像。<br/>            0 指定阴影不得改变。<br/>            0 < value ≤ 100<br/>            指定低于此阈值的阴影强度百分比被加暗。 |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

初始化 EmfPlusLevelsEffect 类的新实例

