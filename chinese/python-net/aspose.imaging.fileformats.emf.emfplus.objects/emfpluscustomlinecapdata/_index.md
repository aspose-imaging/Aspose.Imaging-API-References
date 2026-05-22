---
title: "EmfPlusCustomLineCapData 类"
type: docs
weight: 270
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | 初始化 EmfPlusCustomLineCapData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | 获取或设置 32 位无符号整数，该整数指定来自 LineCap 枚举（第 2.1.1.18 节）的值 <br/>            自定义线帽基于该值。 |
| base_inset | float | r/w | 获取或设置  32 位浮点值，该值指定线帽起点与线段末端之间的距离 <br/>            。 |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | 获取或设置 32 位无符号整数，该整数指定 OptionalData 字段中的数据 |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置 EmfPlusPointF 对象，该对象当前未使用。它必须设置为 {0.0, 0.0}。 |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | 获取或设置  可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节）<br/>             该对象指定自定义图形线帽的附加数据。T<br/>            he 此字段的具体内容由 CustomLineCapDataFlags 字段的值决定 <br/>            。 |
| stroke_end_cap | int | r/w | 获取或设置  32 位无符号整数，该整数指定 LineCap 枚举中的值，以指示在绘制线段末端使用的线帽 <br/>            。 |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置 EmfPlusPointF 对象，该对象当前未使用。它必须设置为 {0.0, 0.0}。 |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | 获取或设置 32 位无符号整数，该整数指定 LineJoin 枚举中的值 <br/>            （第 2.1.1.19 节），该值指定如何连接由同一支笔绘制且端点相接的两条线。在两条线端点的交叉处， <br/>            线段连接使连接看起来更连续。 |
| stroke_miter_limit | float | r/w | 获取或设置  32 位浮点值，该值包含通过设置斜接角连接处厚度的上限<br/>             即斜接长度与线宽的最大允许比例。 |
| stroke_start_cap | int | r/w | 获取或设置  32 位无符号整数，该整数指定 LineCap 枚举中的值，以指示绘制线段起始处使用的线帽 <br/>            。 |
| width_scale | float | r/w | 获取或设置 32 位浮点值，该值指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度，对自定义线帽的缩放量<br/>             。 |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

初始化 EmfPlusCustomLineCapData 类的新实例

