---
title: EmfPlusCustomLineCapData Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Initializes a new instance of the EmfPlusCustomLineCapData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) <br/>            on which the custom line cap is based. |
| base_inset | float | r/w | Gets or sets  32-bit floating-point value that specifies the distance between the beginning <br/>            of the line cap and the end of the line. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Gets or sets  optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14)<br/>             that specifies additional data for the custom graphics line cap. T<br/>            he specific contents of this field are determined <br/>            by the value of the CustomLineCapDataFlags field. |
| stroke_end_cap | int | r/w | Gets or sets  32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what <br/>            line cap is to be used at the end of the line to be drawn. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration <br/>            (section 2.1.1.19), which specifies how to join two lines that are drawn by<br/>             the same pen and whose ends meet. At the intersection of the two line ends, <br/>            a line join makes the connection look more continuous. |
| stroke_miter_limit | float | r/w | Gets or sets  32-bit floating-point value that contains the limit of the thickness<br/>             of the join on a mitered corner by setting  the maximum allowed ratio<br/>             of miter length to line width. |
| stroke_start_cap | int | r/w | Gets or sets  32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the <br/>            line cap used at the start of the line to be drawn |
| width_scale | float | r/w | Gets or sets 32-bit floating-point value that specifies the amount by which to<br/>             scale the custom line cap with respect to the width of the EmfPlusPen <br/>            object (section 2.2.1.7) that is used to draw the lines. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Initializes a new instance of the EmfPlusCustomLineCapData class

