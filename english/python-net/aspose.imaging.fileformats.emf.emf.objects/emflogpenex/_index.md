---
title: EmfLogPenEx Class
type: docs
weight: 190
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfLogPenEx type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfLogPenEx()|Initializes a new instance of the EmfLogPenEx class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|pen_style|Gets or sets the pen style|
|argb_32_color_ref|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). The interpretation of this<br/>            field depends on the BrushStyle value, as shown in the table later in this section.|
|width|Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen.<br/>            If the pen type in the PenStyle field is PS_GEOMETRIC, this value is the width in<br/>             logical units; otherwise, the width is specified in device units. <br/>            If the pen type in the PenStyle field is PS_COSMETIC, this value MUST be 0x00000001.|
|brush_style|Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the<br/>            WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). <br/>            If the pen type in the PenStyle field is PS_GEOMETRIC, this value MUST be either <br/>            BS_SOLID or BS_HATCHED. The value of this field can be BS_NULL, but only if the <br/>            line style specified in PenStyle is PS_NULL. The BS_NULL style SHOULD be used <br/>            to specify a brush that has no effect.|
|brush_hatch|Gets or sets the brush hatch pattern. The definition of this field depends on the <br/>            BrushStyle value, as shown in the table later in this section.|
|num_style_entities|Gets the number of elements in the array specified in the StyleEntry field. <br/>            This value SHOULD be zero if PenStyle does not specify PS_USERSTYLE.|
|style_entry|Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of <br/>            dashes and gaps in the line drawn by this pen, when the value of PenStyle <br/>            is PS_USERSTYLE line style for the pen. The array contains a number of <br/>            entries specified by NumStyleEntries, but it is used as if it repeated indefinitely <br/>            The first entry in the array specifies the length of the first dash. The second <br/>            entry specifies the length of the first gap. Thereafter, lengths of dashes and gaps alternate.<br/>            If the pen type in the PenStyle field is PS_GEOMETRIC, the lengths are specified in <br/>            logical units; otherwise, the lengths are specified in device units.|
|brush_dib_pattern|Gets or sets the brush dib pattern.|
