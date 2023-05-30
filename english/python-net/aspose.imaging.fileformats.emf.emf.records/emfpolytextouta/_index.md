---
title: EmfPolyTextOutA Class
type: docs
weight: 850
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---

The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutA

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPolyTextOutA type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPolyTextOutA(source)|Initializes a new instance of the EmfPolyTextOutA class|
|EmfPolyTextOutA()|Initializes a new instance of the [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the <br/>            bounding rectangle in device units.|
|graphics_mode|Gets or sets a 32-bit unsigned integer that specifies the current graphics mode, <br/>            from the GraphicsMode enumeration (section 2.1.16).|
|ex_scale|Gets or sets a 32-bit floating-point value that specifies the X scale from page units to <br/>            .01mm units if graphics mode is GM_COMPATIBLE.|
|ey_scale|Gets or sets a 32-bit floating-point value that specifies the Y scale from page units to <br/>            .01mm units if graphics mode is GM_COMPATIBLE.|
|a_emr_text|Gets or sets an array of EmrText objects (section 2.2.5) that specify the output <br/>            strings in 8-bit ASCII characters, with text attributes, and spacing values. The number of <br/>            EmrText objects is specified by cStrings.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
