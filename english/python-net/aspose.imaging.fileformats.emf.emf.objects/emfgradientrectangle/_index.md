---
title: EmfGradientRectangle Class
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---

The GradientRectangle object defines a rectangle using TriVertex objects (section 2.2.26) in an <br/>            EMR_GRADIENTFILL record (section 2.3.5.12).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle

**Inheritance:** EmfObject

**Aspose.Imaging Version:** 23.6

The EmfGradientRectangle type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfGradientRectangle()](#EmfGradientRectangle__0) | Initializes a new instance of the EmfGradientRectangle class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| upper_left | int | r/w | Gets or sets an index into an array of TriVertex objects that specifies the upper-left <br/>            vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the <br/>            nVer field of the EMR_GRADIENTFILL record. |
| lower_right | int | r/w | Gets or sets an index into an array of TriVertex objects that specifies the lower-right <br/>            vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the <br/>            nVer field of the EMR_GRADIENTFILL record. |

### EmfGradientRectangle() {#EmfGradientRectangle__0}


```
 EmfGradientRectangle() 
```

Initializes a new instance of the EmfGradientRectangle class

