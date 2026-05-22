---
title: "EmfPlusPathGradientBrushData 类"
type: docs
weight: 500
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | 初始化 EmfPlusPathGradientBrushData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | 获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条指定。<br/>如果在 BrushDataFlags 字段中设置了 BrushDataPath 标志，则此字段必须包含一个 EmfPlusBoundaryPathData 对象（第 2.2.2.6 节）；<br/>否则，此字段必须包含一个 EmfPlusBoundaryPointData 对象（第 2.2.2.7 节）。 |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | 获取或设置指定 OptionalData 字段中数据的 32 位无符号整数。<br/>此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与路径渐变画笔相关： |
| center_argb_32_color | int | r/w | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。<br/>画笔的颜色从边界颜色逐渐过渡到中心颜色，随着从边界移动到中心点而变化。 |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置 EmfPlusARGB 对象（第 2.2.1 节），该对象指定路径渐变画笔的中心颜色，<br/>即画笔中心点出现的颜色。画笔的颜色从边界颜色逐渐过渡到中心颜色，随着从边界移动到中心点而变化。 |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | 获取或设置一个可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），该对象<br/>指定路径渐变画笔的附加数据。<br/>此字段的具体内容由 BrushDataFlags 字段的值决定。 |
| surrounding_argb_32_colors | int[] | r/w | 获取或设置一个包含 SurroundingColorCount 个 EmfPlusARGB 对象的数组，<br/>这些对象指定画笔边界上离散点的颜色。 |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | 获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，该整数指定<br/>是否绘制画笔边界之外的区域。在绘制边界之外时，包装模式指定颜色渐变的重复方式。 |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

初始化 EmfPlusPathGradientBrushData 类的新实例

