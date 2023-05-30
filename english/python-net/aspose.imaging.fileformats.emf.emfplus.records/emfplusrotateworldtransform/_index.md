---
title: EmfPlusRotateWorldTransform Class
type: docs
weight: 410
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusRotateWorldTransform type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusRotateWorldTransform(source)|Initializes a new instance of the EmfPlusRotateWorldTransform class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|post_multiplied_matrix|Gets a value indicating whether [post multiplied matrix].<br/>            If set, the transform matrix should be post-multiplied. If clear, it should be premultiplied.|
|angle|Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees.<br/>            The operation is performed by constructing a new transform matrix from the following<br/>            diagram:<br/>            ---------------------------------<br/>            |  sin(Angle) |  cos(Angle) | 0 |<br/>            |  cos(Angle) |  sin(Angle) | 0 |<br/>            ---------------------------------<br/>            Figure 2: Rotation Transform Matrix<br/>            The current world space transform is multiplied by this matrix, and the result becomes the<br/>            new current world space transform. The Flags field determines the order of multiplication.|
