---
title: EmfPlusRotateWorldTransform.Angle
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusRotateWorldTransform property. Gets or sets a 32bit floatingpoint value that specifies the angle of rotation in degrees. The operation is performed by constructing a new transform matrix from the following diagram   sinAngle  cosAngle  0   cosAngle  sinAngle  0   Figure 2 Rotation Transform Matrix The current world space transform is multiplied by this matrix and the result becomes the new current world space transform. The Flags field determines the order of multiplication
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/
---
## EmfPlusRotateWorldTransform.Angle property

Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. The operation is performed by constructing a new transform matrix from the following diagram: --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- Figure 2: Rotation Transform Matrix The current world space transform is multiplied by this matrix, and the result becomes the new current world space transform. The Flags field determines the order of multiplication.

```csharp
public float Angle { get; set; }
```

### Property Value

The angle.

### See Also

* class [EmfPlusRotateWorldTransform](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusrotateworldtransform/)
* assembly [Aspose.Imaging](../../../)


