---
title: EmfPolyTextOutW Class
type: docs
weight: 860
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPolyTextOutW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPolyTextOutW(source)|Initializes a new instance of the EmfPolyTextOutW class|
|EmfPolyTextOutW()|Initializes a new instance of the [EmfPolyTextOutW](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the <br/>            bounding rectangle in device units.|
|graphics_mode|Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, <br/>            from the GraphicsMode enumeration (section 2.1.16).|
|ex_scale|Gets or sets a 32-bit floating-point value that specifies the X scale from page units to <br/>            .01mm units if graphics mode is GM_COMPATIBLE.|
|ey_scale|Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to <br/>            .01mm units if graphics mode is GM_COMPATIBLE.|
|w_emr_text|Gets or sets an array of EmrText objects (section 2.2.5) that specify the output <br/>            strings in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values. The <br/>            number of EmrText objects is specified by cStrings.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
