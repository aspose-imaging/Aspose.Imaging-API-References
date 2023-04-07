---
title: EmfSmallTextOut Class
type: docs
weight: 1350
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

The EMR_SMALLTEXTOUT record outputs a string.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfSmallTextOut type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfSmallTextOut(source)|Initializes a new instance of the EmfSmallTextOut class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|x|Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string.|
|y|Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string.|
|c_chars|Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the<br/>            string. The string is NOT null-terminated.|
|fu_options|Gets or sets a 32-bit unsigned integer specifying the text output options to use. These<br/>            options are specified by one or a combination of values from the ExtTextOutOptions<br/>            enumeration (section 2.1.11).|
|graphics_mode|Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the<br/>            GraphicsMode enumeration (section 2.1.16).|
|ex_scale|Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction.|
|ey_scale|Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction.|
|bounds|Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that<br/>            specifies the bounding rectangle in device units.|
|text_string|Gets or sets a variable-length string that contains the text string to draw, in either<br/>            8-bit or 16-bit character codes, according to the value of the fuOptions field.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
