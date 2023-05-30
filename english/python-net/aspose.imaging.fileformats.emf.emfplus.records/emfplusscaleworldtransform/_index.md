---
title: EmfPlusScaleWorldTransform Class
type: docs
weight: 430
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusScaleWorldTransform type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusScaleWorldTransform(source)|Initializes a new instance of the EmfPlusScaleWorldTransform class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|post_multiplied_matrix|Gets a value indicating whether [post multiplied matrix].<br/>            If set, the transform matrix should be post-multipled. If clear, it should be premultiplied.|
|sx|Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. The scaling<br/>            is performed by constructing a new transform matrix from the Sx and Sy field values, as<br/>            shown in the following table.<br/>            -----------------<br/>            |  Sx |   0 | 0 |<br/>            |   0 |  Sx | 0 |<br/>            -----------------<br/>            Figure 3: Scale Transform Matrix|
|sy|Gets or sets a 32-bit floating-point value that defines the vertical scale factor.|
