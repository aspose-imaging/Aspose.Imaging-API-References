---
title: "EmfPlusBlendColors 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | 初始化 EmfPlusBlendColors 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | 获取或设置一个 PositionCount EmfPlusARGB 对象数组（第 2.2.2.1 节），该数组 <br/>            指定 BlendPositions 字段中定义位置的颜色。 |
| blend_positions | float[] | r/w | 获取或设置混合位置<br/>            一个 PositionCount 32 位浮点值数组<br/>            指定沿渐变线的距离比例。<br/>            每个元素必须是介于 0.0 到 1.0（含）之间的数字。<br/>            对于线性渐变画刷，0.0 表示起始点<br/>            而 1.0 表示结束点。对于路径渐变画刷，<br/>            0.0 表示中点，1.0 表示端点 |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

初始化 EmfPlusBlendColors 类的新实例

