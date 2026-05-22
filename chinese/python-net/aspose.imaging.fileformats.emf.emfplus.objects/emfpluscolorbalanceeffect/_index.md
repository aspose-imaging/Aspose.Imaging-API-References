---
title: "EmfPlusColorBalanceEffect 类"
type: docs
weight: 170
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---

**Summary:** The ColorBalanceEffect object specifies adjustments to the relative amounts of red, green, and blue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorBalanceEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect__1) | 初始化 EmfPlusColorBalanceEffect 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| cyan_red | int | r/w | 获取或设置一个 32 位有符号整数，指定图像中红色量的变化。<br/>            此值必须在 -100 到 100 的范围内，效果如下：<br/>            -100 ≤ value < 0<br/>            当值减小时，图像中的红色量应减少，而青色量应增加。<br/>            0 值为 0 时，红色和青色的量必须不变。<br/>            0 < value ≤ 100<br/>            当值增大时，图像中的红色量应增加，而青色量应减少。 |
| magenta_green | int | r/w | 获取或设置一个 32 位有符号整数，指定图像中绿色量的变化。此值必须在 -100 到 100 的范围内，效果如下：<br/>-100 ≤ value < 0<br/>当值减小时，图像中的绿色量应减少，而品红量应增加。<br/>0 值为 0 时，绿色和品红的量必须不变。<br/>0 < value ≤ 100<br/>当值增大时，图像中的绿色量应增加，而品红量应减少。 |
| yellow_blue | int | r/w | 获取或设置一个 32 位有符号整数，指定图像中蓝色量的变化。此值必须在 -100 到 100 的范围内，效果如下：<br/>-100 ≤ value < 0<br/>当值减小时，图像中的蓝色量应减少，而黄色量应增加。<br/>0 值为 0 时，蓝色和黄色的量必须不变。<br/>0 < value ≤ 100<br/>当值增大时，图像中的蓝色量应增加，而黄色量应减少。 |


### Constructor: EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect__1}


```
 EmfPlusColorBalanceEffect() 
```

初始化 EmfPlusColorBalanceEffect 类的新实例

