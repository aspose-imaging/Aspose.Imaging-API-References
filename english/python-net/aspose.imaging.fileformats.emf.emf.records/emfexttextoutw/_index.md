---
title: EmfExtTextOutW Class
type: docs
weight: 470
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---

The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutW

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfExtTextOutW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfExtTextOutW(source)|Initializes a new instance of the EmfExtTextOutW class|
|EmfExtTextOutW()|Initializes a new instance of the [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19). It is not used and <br/>            MUST be ignored on receipt.|
|graphics_mode|Gets or sets a 32-bit unsigned integer that specifies the graphics mode from the <br/>            GraphicsMode enumeration (section 2.1.16).|
|ex_scale|Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along <br/>            the X axis to convert from page space units to .01mm units. This SHOULD be used only if the <br/>            graphics mode specified by iGraphicsMode is GM_COMPATIBLE.|
|ey_scale|Gets or sets a 32-bit floating-point value that specifies the scale factor to apply along <br/>            the Y axis to convert from page space units to .01mm units. This SHOULD be used only if the <br/>            graphics mode specified by iGraphicsMode is GM_COMPATIBLE.|
|w_emr_text|Gets or sets an EmrText object (section 2.2.5) that specifies the output string in 16-bit Unicode UTF16-LE characters, with text attributes and spacing values.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
