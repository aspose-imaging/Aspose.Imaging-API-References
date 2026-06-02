---
title: "EmfPlusPenOptionalData 类"
type: docs
weight: 560
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | 初始化 EmfPlusPenOptionalData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | 获取或设置可选 EmfPlusCompoundLineData 对象（section 2.2.2.9） <br/>            指定一个浮点值数组，用于定义笔的复合线，该复合线由平行线和间隔组成。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。 |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | 获取或设置可选的 EmfPlusCustomEndCapData 对象（section 2.2.2.11）<br/>            定义自定义结束帽形状，即使用此笔绘制的线段末端的形状。它可以是多种形状之一，例如方形、圆形或菱形。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。 |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | 获取或设置可选的 EmfPlusCustomStartCapData 对象（section 2.2.2.15）<br/>            定义自定义起始帽形状，即使用此笔绘制的线段起始端的形状。它可以是多种形状之一，例如方形、圆形或菱形。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。 |
| dash_offset | float | r/w | 获取或设置可选的 32 位浮点值，指定从线段起点到虚线模式中第一个空格起点的距离。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。 |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | 获取或设置可选的 32 位有符号整数，指定虚线中每个短划线两端的形状。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且该值必须在 DashedLineCapType 枚举（section 2.1.1.10）中定义。 |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | 获取或设置可选的 EmfPlusDashedLineData 对象（section 2.2.2.16）<br/>            用于指定自定义虚线中短划线和空格的长度。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。 |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段末端的形状。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举中定义。 |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | 获取或设置可选的 32 位有符号整数，指定如何连接由同一支笔绘制且端点相接的两条线。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且该值必须在 LineJoinType 枚举（section 2.1.1.19）中定义。 |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。若在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且该值必须在 LineStyle 枚举（section 2.1.1.20）中定义。 |
| miter_limit | float | r/w | 获取或设置可选的 32 位浮点值，用于指定斜接 <br/> 限制，即斜接长度与<br/> 线宽的最大允许比例。斜接长度是从<br/> 连接内部的线壁交点到 <br/> 连接外部的线壁交点的距离。<br/> 当两条线之间的角度很小，斜接长度可能会很大。此字段必须在 <br/> PenDataMiterLimit 标志在 PenDataFlags 字段中被设置时出现于 EmfPlusPenData 对象。 |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | 获取或设置可选的 32 位有符号整数，用于指定 <br/> 笔宽相对于绘制线条坐标的分布。此字段必须在 <br/> PenDataNonCenter 标志在 PenDataFlags 字段中被设置时出现，并且该值必须在 PenAlignment <br/> 枚举（第 2.1.1.24 节）中定义。 |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | 获取或设置可选的 32 位有符号整数，用于指定 <br/> 线段起始形状，存于 CustomStartCapData 字段中。 <br/> 若 PenDataStartCap 标志在 PenDataFlags 字段中被设置，则此字段必须存在，并且该值必须在 LineCapType 枚举 <br/>（第 2.1.1.18 节）中定义。 |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节） <br/> 指定笔的世界坐标到设备坐标的变换。若 PenDataTransform 标志在 EmfPlusPenData 对象的 PenDataFlags 字段中被设置，则此字段必须存在。 |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

初始化 EmfPlusPenOptionalData 类的新实例

