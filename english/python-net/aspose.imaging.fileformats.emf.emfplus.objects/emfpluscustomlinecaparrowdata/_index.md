---
title: EmfPlusCustomLineCapArrowData Class
type: docs
weight: 260
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---

**Summary:** The EmfPlusCustomLineCapArrowData object specifies adjustable arrow data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapArrowData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData__1) | Initializes a new instance of the EmfPlusCustomLineCapArrowData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| fill_state | bool | r/w | Gets or sets a 32-bit Boolean value that specifies whether the arrow cap is filled. If the arrow cap is <br/>            not filled, only the outline is drawn |
| height | float | r/w | Gets or sets a 32-bit floating-point value that specifies <br/>            the height of the arrow cap. |
| line_end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap to <br/>            be used at the end of the line to be drawn |
| line_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets an EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| line_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the value in the LineJoin <br/>            enumeration that specifies how to join two lines that are drawn by <br/>            the same pen and whose ends meet. At the intersection of the two line ends, <br/>            a line join makes the connection look more continuous. |
| line_miter_limit | float | r/w | Gets or sets a 32-bit floating-point value that specifies the limit of the<br/>             thickness of the join on a mitered corner by setting <br/>            the maximum allowed ratio of miter length to line width |
| line_start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap to <br/>            be used at the start of the line to be drawn |
| middle_inset | float | r/w | Gets or sets a 32-bit floating-point value that specifies the number of pixels between the outline of the arrow<br/>             cap and the fill of the arrow cap. |
| width | float | r/w | Gets or sets a 32-bit floating-point value that specifies <br/>            the width of the arrow cap |
| width_scale | float | r/w | Gets or sets a 32-bit floating-point value that specifies the amount by <br/>            which to scale an EmfPlusCustomLineCap object with respect to the width <br/>            of the graphics pen that is used to draw the lines |


### Constructor: EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData__1}


```
 EmfPlusCustomLineCapArrowData() 
```

Initializes a new instance of the EmfPlusCustomLineCapArrowData class

