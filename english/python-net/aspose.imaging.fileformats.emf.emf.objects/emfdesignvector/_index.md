---
title: EmfDesignVector Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfDesignVector type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfDesignVector()|Initializes a new instance of the EmfDesignVector class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|signature|Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664.|
|num_axes|Gets or sets a 32-bit unsigned integer that specifies the number of elements in <br/>            the Values array. It MUST be in the range 0 to 16, inclusive|
|values|Gets or sets an optional array of 32-bit signed integers that specify the values <br/>            of the font axes of a multiple master, OpenType font. The maximum number of values in the array is 16.|
