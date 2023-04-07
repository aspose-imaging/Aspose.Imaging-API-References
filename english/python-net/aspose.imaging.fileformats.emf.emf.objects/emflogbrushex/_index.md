---
title: EmfLogBrushEx Class
type: docs
weight: 120
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfLogBrushEx type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfLogBrushEx()|Initializes a new instance of the EmfLogBrushEx class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|brush_style|Gets or sets a 32-bit unsigned integer that specifies the brush style. The value MUST <br/>            be an enumeration from WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). The style <br/>            values that are supported in this structure are listed later in this section. The BS_NULL style <br/>            SHOULD be used to specify a brush that has no effect.|
|argb_32_color_ref|Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a<br/>            color. The interpretation of this field depends on the value of BrushStyle, as explained in the<br/>            following table.|
|brush_hatch|Gets or sets a 32-bit unsigned field that contains the brush hatch data. Its <br/>            interpretation depends on the value of BrushStyle,|
