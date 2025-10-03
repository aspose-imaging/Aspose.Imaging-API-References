---
title: EmfEpsData Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Initializes a new instance of the EmfEpsData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Gets or sets an array of three Point28_4 objects (section 2.2.23) that defines the <br/>            coordinates of the output parallelogram using 28.4 bit FIX notation |
| post_script_data | System.Byte | r/w | Gets or sets an array of bytes of PostScript data. The length of this array can <br/>            be computed from the SizeData field. This data MAY be used to render an image. |
| size_data | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes |
| version | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. This <br/>            value MUST be 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Initializes a new instance of the EmfEpsData class

