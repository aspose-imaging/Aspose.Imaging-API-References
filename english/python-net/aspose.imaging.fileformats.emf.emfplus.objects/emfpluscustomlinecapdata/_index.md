---
title: EmfPlusCustomLineCapData Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusCustomLineCapData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusCustomLineCapData()|Initializes a new instance of the EmfPlusCustomLineCapData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|custom_line_cap_data_flags|Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field|
|base_cap|Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) <br/>            on which the custom line cap is based.|
|base_inset|Gets or sets  32-bit floating-point value that specifies the distance between the beginning <br/>            of the line cap and the end of the line.|
|stroke_start_cap|Gets or sets  32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the <br/>            line cap used at the start of the line to be drawn|
|stroke_end_cap|Gets or sets  32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what <br/>            line cap is to be used at the end of the line to be drawn.|
|stroke_join|Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration <br/>            (section 2.1.1.19), which specifies how to join two lines that are drawn by<br/>             the same pen and whose ends meet. At the intersection of the two line ends, <br/>            a line join makes the connection look more continuous.|
|stroke_miter_limit|Gets or sets  32-bit floating-point value that contains the limit of the thickness<br/>             of the join on a mitered corner by setting  the maximum allowed ratio<br/>             of miter length to line width.|
|width_scale|Gets or sets 32-bit floating-point value that specifies the amount by which to<br/>             scale the custom line cap with respect to the width of the EmfPlusPen <br/>            object (section 2.2.1.7) that is used to draw the lines.|
|fill_hot_spot|Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}.|
|stroke_hot_spot|Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}.|
|optional_data|Gets or sets  optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14)<br/>             that specifies additional data for the custom graphics line cap. T<br/>            he specific contents of this field are determined <br/>            by the value of the CustomLineCapDataFlags field.|
