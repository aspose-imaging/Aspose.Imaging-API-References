---
title: "EmfColorAdjustment 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | 初始化 EmfColorAdjustment 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | 获取或设置一个 16 位无符号整数，指定源颜色的 <br/>            蓝色基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。 <br/>            值为 10,000 表示不得执行伽马校正。 |
| 亮度 | int | r/w | 获取或设置一个 16 位有符号整数，指定要应用于源对象的亮度量。<br/>            此值应在 –100 到 100 的范围内。<br/>            值为零表示不得执行亮度调整。 |
| colorfullness | int | r/w | 获取或设置一个 16 位有符号整数，指定要应用于源对象的色彩丰富度。<br/>            此值应在 –100 到 100 的范围内。 <br/>            值为零表示不得执行色彩丰富度调整 |
| 对比度 | int | r/w | 获取或设置一个 16 位有符号整数，指定要应用于源对象的对比度。<br/>            此值应在 –100 到 100 的范围内。值为零表示不得执行对比度调整。 |
| green_gamma | int | r/w | 获取或设置一个 16 位无符号整数，指定源颜色的绿色 <br/>            基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。 <br/>            值为 10,000 表示不得执行伽马校正。 |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | 获取或设置一个 16 位无符号整数，指定查看图像时所使用的标准光源类型，来自 <br/>            Illuminant 枚举（第 2.1.19 节）。 |
| red_gamma | int | r/w | 获取或设置一个 16 位无符号整数，指定源颜色的红色 <br/>            基色的 n 次幂伽马校正值。此值应在 2,500 到 65,000 的范围内。<br/>            值为 10,000 表示不得执行伽马校正。 |
| red_green_tint | int | r/w | 获取或设置 16 位有符号整数，指定要应用于源对象的红色或绿色色调调整量。<br/>            此值应在 –100 到 100 的范围内。<br/>            正数向红色调整，负数向绿色调整。<br/>            值为零表示不得执行色调调整 |
| reference_black | int | r/w | 获取或设置一个 16 位无符号整数，指定源颜色的黑色参考值。<br/>            任何比此更暗的颜色都视为黑色。<br/>            此值应在零到 4,000 的范围内 |
| reference_white | int | r/w | 获取或设置一个 16 位无符号整数，指定源颜色的白色参考值。<br/>            任何比此更亮的颜色都视为白色。<br/>            此值应在 6,000 到 10,000 的范围内。 |
| size | int | r/w | 获取或设置一个 16 位无符号整数，指定此对象的字节大小。此值必须为 0x0018。 |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | 获取或设置一个 16 位无符号整数，指定如何准备输出图像。此字段可以 <br/>            设置为 NULL 或 ColorAdjustment 枚举中的任意组合值（第 2.1.5 节）。 |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

初始化 EmfColorAdjustment 类的新实例

