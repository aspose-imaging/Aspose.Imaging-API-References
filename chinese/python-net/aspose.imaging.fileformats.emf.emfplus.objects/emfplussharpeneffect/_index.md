---
title: "EmfPlusSharpenEffect 类"
type: docs
weight: 630
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---

**Summary:** The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusSharpenEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect__1) | 初始化 EmfPlusSharpenEffect 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| amount | float | r/w | 获取或设置一个 32 位浮点数，用于指定给定像素与周围像素之间的强度差异。<br/>            0 表示不应执行锐化。<br/>            0 &lt; value ≤ 100<br/>            随着该值的增大，像素之间的强度差异应当<br/>            增加。 |
| 半径 | float | r/w | 获取或设置一个 32 位浮点数，指定以像素为单位的锐化半径，<br/>            该半径决定在计算给定像素的新值时涉及的像素数量。<br/>            随着此值的增大，参与计算的像素数量增加，<br/>            结果位图 应该会变得更清晰。 |


### Constructor: EmfPlusSharpenEffect() {#EmfPlusSharpenEffect__1}


```
 EmfPlusSharpenEffect() 
```

初始化 EmfPlusSharpenEffect 类的新实例

