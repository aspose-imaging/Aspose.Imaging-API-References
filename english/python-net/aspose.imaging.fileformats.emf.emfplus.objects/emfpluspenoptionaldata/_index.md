---
title: EmfPlusPenOptionalData Class
type: docs
weight: 560
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Initializes a new instance of the EmfPlusPenOptionalData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) <br/>            that specifies an array of floating-point values that define <br/>            the compound line of a pen, which is made up of parallel lines <br/>            and spaces. This field MUST be present if the <br/>            PenDataCompoundLine flag is set in the PenDataFlags field <br/>            of the EmfPlusPenData object |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) <br/>            that defines the custom end-cap shape, which is the shape to <br/>            use at the end of a line drawn with this pen. It can be any of <br/>            various shapes, such as a square, circle, or diamond. This <br/>            field MUST be present if the PenDataCustomEndCap flag is <br/>            set in the PenDataFlags field of the EmfPlusPenData object |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) <br/>            that defines the custom start-cap shape, which is the shape to <br/>            use at the start of a line drawn with this pen. It can be any <br/>            of various shapes, such as a square, circle, or diamond. <br/>            This field MUST be present if the PenDataCustomStartCap flag <br/>            is set in the PenDataFlags field of the EmfPlusPenData object |
| dash_offset | float | r/w | Gets or sets optional 32-bit floating-point value that specifies the <br/>            distance from the start of a line to the start of the <br/>            first space in a dashed line pattern. This field MUST be <br/>            present if the PenDataDashedLineOffset flag is set in the <br/>            PenDataFlags field of the EmfPlusPenData object. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Gets or sets optional 32-bit signed integer that specifies the shape for <br/>            both ends of each dash in a dashed line. This field MUST be <br/>            present if the PenDataDashedLineCap flag is set in the <br/>            PenDataFlags field of the EmfPlusPenData object, and the <br/>            value MUST be defined in the DashedLineCapType enumeration <br/>            (section 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) <br/>            that specifies the lengths of dashes and spaces in a custom <br/>            dashed line. This field MUST be present if the PenDataDashedLine <br/>            flag is set in the PenDataFlags field of the EmfPlusPenData<br/>            object. |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Gets or sets optional 32-bit signed integer that specifies the shape<br/>             for the end of a line in the CustomEndCapData field. This <br/>            field MUST be present if the PenDataEndCap flag is set in the <br/>            PenDataFlags field of the EmfPlusPenData object, and the value <br/>            MUST be defined in the LineCapType enumeration |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Gets or sets an optional 32-bit signed integer that specifies how to join<br/>             two lines that are drawn by the same pen and whose ends meet. <br/>            This field MUST be present if the PenDataJoin flag is set in <br/>            the PenDataFlags field of the EmfPlusPenData object, and the <br/>            value MUST be defined in the LineJoinType enumeration <br/>            (section 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Gets or sets optional 32-bit signed integer that specifies the style <br/>            used for lines drawn with this pen object. This field MUST <br/>            be present if the PenDataLineStyle flag is set in the <br/>            PenDataFlags field of the EmfPlusPenData object, and the <br/>            value MUST be defined in the LineStyle enumeration <br/>            (section 2.1.1.20). |
| miter_limit | float | r/w | Gets or sets optional 32-bit floating-point value that specifies the miter <br/>            limit, which is the maximum allowed ratio of miter length to<br/>            line width. The miter length is the distance from the<br/>            intersection of the line walls on the inside the join to <br/>            the intersection of the line walls outside the join. <br/>            The miter length can be large when the angle between two <br/>            lines is small. This field MUST be present if the <br/>            PenDataMiterLimit flag is set in the PenDataFlags field <br/>            of the EmfPlusPenData object. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Gets or sets optional 32-bit signed integer that specifies the <br/>            distribution of the pen width with respect to the <br/>            coordinates of the line being drawn. This field MUST <br/>            be present if the PenDataNonCenter flag is set in the <br/>            PenDataFlags field of the EmfPlusPenData object, and <br/>            the value MUST be defined in the PenAlignment <br/>            enumeration (section 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Gets or sets an optional 32-bit signed integer that specifies the shape for<br/>             the start of a line in the CustomStartCapData field. <br/>            This field MUST be present if the PenDataStartCap flag is set <br/>            in the PenDataFlags field of the EmfPlusPenData object, and the<br/>             value MUST be defined in the LineCapType enumeration <br/>            (section 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) <br/>            that specifies a world space to device space transform for <br/>            the pen. This field MUST be present if the PenDataTransform <br/>            flag is set in the PenDataFlags field of the EmfPlusPenData <br/>            object. |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Initializes a new instance of the EmfPlusPenOptionalData class

