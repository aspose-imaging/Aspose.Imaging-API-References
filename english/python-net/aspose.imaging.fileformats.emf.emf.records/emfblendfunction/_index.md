---
title: EmfBlendFunction Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

A structure that specifies the blending operations for source and destination bitmaps.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfBlendFunction type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfBlendFunction(dword_data)|Initializes a new instance of the EmfBlendFunction class|
|EmfBlendFunction()|Initializes a new instance of the EmfBlendFunction class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|blend_operation|Gets the blend operation code. <br/>            The only source and destination <br/>            blend operation that has been defined is 0x00, which specifies that the source bitmap <br/>            MUST be combined with the destination bitmap based on the alpha transparency values <br/>            of the source pixels. See the following equations for details.|
|blend_flags|Gets the blend flags.<br/>            This value MUST be 0x00 and MUST be ignored.|
|src_constant_alpha|Gets an 8-bit unsigned integer that specifies alpha transparency, <br/>            which determines the blend of the source and destination bitmaps. This value MUST be <br/>            used on the entire source bitmap. The minimum alpha transparency value, zero, <br/>            corresponds to completely transparent the maximum value, 0xFF, corresponds to <br/>            completely opaque. In effect, a value of 0xFF specifies that the per-pixel alpha values <br/>            determine the blend of the source and destination bitmaps. See the equations later in <br/>            this section for details.|
|alpha_format|Gets a structure that specifies how source and destination pixels are <br/>            interpreted with respect to alpha transparency.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|to_int()|Converts the string representation of a number to an integer.|
