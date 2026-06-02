---
title: "EmfPlusTintEffect 类"
type: docs
weight: 700
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---

**Summary:** The TintEffect object specifies an addition of black or white to a specified hue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTintEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect__1) | 初始化 EmfPlusTintEffect 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| amount | int | r/w | 获取或设置一个 32 位有符号整数，指定色相的增强或削弱程度。<br/>            -100 ≤ value &lt; 0<br/>            负值表示色相被削弱，相当于加入黑色。<br/>            0 值为 0 表示必须不改变色调。<br/>            0 &lt; value ≤ 100<br/>            正值表示色相被增强，相当于加入白色。 |
| 色相 | int | r/w | 获取或设置一个 32 位有符号整数，指定对色调效果应用的色相。<br/>            -180 ≤ value < 0 <br/>            从蓝色开始，逆时针旋转色轮到指定角度的颜色。<br/>            0 值为 0 表示色轮上的蓝色。<br/>            0 < value ≤ 180<br/>            从蓝色开始，顺时针旋转色轮到指定角度的颜色。 |


### Constructor: EmfPlusTintEffect() {#EmfPlusTintEffect__1}


```
 EmfPlusTintEffect() 
```

初始化 EmfPlusTintEffect 类的新实例

