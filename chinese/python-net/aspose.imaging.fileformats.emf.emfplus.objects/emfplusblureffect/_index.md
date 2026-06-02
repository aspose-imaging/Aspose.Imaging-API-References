---
title: "EmfPlusBlurEffect 类"
type: docs
weight: 100
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | 初始化 EmfPlusBlurEffect 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | 获取或设置 一个 32 位浮点数，指定以像素为单位的模糊半径，<br/> 该半径决定在计算给定像素的新值时涉及的像素数量。<br/> 此值必须在 0.0 到 255.0 的范围内。 |
| expand_edge | bool | r/w | 获取或设置 一个 32 位布尔值，指定位图是否按模糊半径的数值扩展以产生柔和边缘。此值必须是以下之一：<br/> FALSE<br/> 0x00000000<br/> 位图的大小不得改变，其柔和边缘应被裁剪到模糊半径的大小。<br/> TRUE<br/> 0x00000001<br/> 位图的大小应按模糊半径的数值扩展，以产生柔和边缘。 |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

初始化 EmfPlusBlurEffect 类的新实例。

