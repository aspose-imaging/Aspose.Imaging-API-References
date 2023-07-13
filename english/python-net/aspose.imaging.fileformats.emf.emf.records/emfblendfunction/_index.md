---
title: EmfBlendFunction Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

**Aspose.Imaging Version:** 23.6

The EmfBlendFunction type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_0) | Initializes a new instance of the [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) class. |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Initializes a new instance of the EmfBlendFunction class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| blend_operation | byte | r | Gets the blend operation code. <br/>            The only source and destination <br/>            blend operation that has been defined is 0x00, which specifies that the source bitmap <br/>            MUST be combined with the destination bitmap based on the alpha transparency values <br/>            of the source pixels. See the following equations for details. |
| blend_flags | byte | r | Gets the blend flags.<br/>            This value MUST be 0x00 and MUST be ignored. |
| src_constant_alpha | byte | r | Gets an 8-bit unsigned integer that specifies alpha transparency, <br/>            which determines the blend of the source and destination bitmaps. This value MUST be <br/>            used on the entire source bitmap. The minimum alpha transparency value, zero, <br/>            corresponds to completely transparent the maximum value, 0xFF, corresponds to <br/>            completely opaque. In effect, a value of 0xFF specifies that the per-pixel alpha values <br/>            determine the blend of the source and destination bitmaps. See the equations later in <br/>            this section for details. |
| alpha_format | EmfBlendFunction.AlphaFormatEnum | r | Gets a structure that specifies how source and destination pixels are <br/>            interpreted with respect to alpha transparency. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_int()](#to_int__2) | Converts the string representation of a number to an integer. |

### EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_0}


```
 EmfBlendFunction(dword_data) 
```

Initializes a new instance of the [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dword_data | int | The dword data. |

### EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Initializes a new instance of the EmfBlendFunction class

### to_int() {#to_int__2}


```
 to_int() 
```

Converts the string representation of a number to an integer.

**Returns**

| Type | Description |
| :- | :- |
| int | The DWORD value of structure. |


