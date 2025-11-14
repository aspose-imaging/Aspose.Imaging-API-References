---
title: EmfPlusPenData Class
type: docs
weight: 550
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Initializes a new instance of the EmfPlusPenData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) <br/>            that specifies additional data for the pen object. The specific <br/>            contents of this field are determined by the value of the <br/>            PenDataFlags field. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Gets or sets 32-bit unsigned integer that specifies the data in the <br/>            OptionalData field. This value MUST be composed of PenData <br/>            flags (section 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Gets or sets 32-bit unsigned integer that specifies the measuring units <br/>            for the pen. The value MUST be from the UnitType enumeration <br/>            (section 2.1.1.33). |
| pen_width | float | r/w | Gets or sets 32-bit floating-point value that specifies the width of the <br/>            line drawn by the pen in the units specified by the PenUnit <br/>            field. If a zero width is specified, a minimum value is used, <br/>            which is determined by the units |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Initializes a new instance of the EmfPlusPenData class

