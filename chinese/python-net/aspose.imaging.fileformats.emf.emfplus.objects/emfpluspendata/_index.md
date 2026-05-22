---
title: "EmfPlusPenData 类"
type: docs
weight: 550
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | 初始化 EmfPlusPenData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | 获取或设置可选的 EmfPlusPenOptionalData 对象（section 2.2.2.34） <br/>            该对象指定笔对象的附加数据。此字段的具体 <br/>            内容由 PenDataFlags 字段的值决定。 |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | 获取或设置一个 32 位无符号整数，指定 <br/>            OptionalData 字段中的数据。此值必须由 PenData <br/>            标志（section 2.1.2.7）组成。 |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | 获取或设置一个 32 位无符号整数，指定笔的测量单位 <br/>            。该值必须来自 UnitType 枚举 <br/>            （section 2.1.1.33）。 |
| pen_width | float | r/w | 获取或设置一个 32 位浮点值，指定宽度 <br/>            笔绘制的线条，单位由 PenUnit <br/>            字段指定。如果指定宽度为零，则使用最小值，<br/>            该最小值由单位决定。 |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

初始化 EmfPlusPenData 类的新实例

