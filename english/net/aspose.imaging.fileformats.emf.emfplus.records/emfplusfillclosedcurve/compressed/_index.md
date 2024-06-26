---
title: EmfPlusFillClosedCurve.Compressed
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusFillClosedCurve property. Gets or sets a value indicating whether this EmfPlusFillClosedCurve is compressed. This bit indicates whether the PointData field specifies compressed data. If set PointData specifies absolute locations in the coordinate space with 16bit integer coordinates. If clear PointData specifies absolute locations in the coordinate space with 32bit floatingpoint coordinates.  A winding fill operation fills areas according to the evenodd parity rule. According to this rule a test point can be determined to be inside or outside a closed curve as follows Draw a line from the test point to a point that is distant from the curve. If that line crosses the curve an odd number of times the test point is inside the curve otherwise the test point is outside the curve.  An alternate fill operation fills areas according to the nonzero rule. According to this rule a test point can be determined to be inside or outside a closed curve as follows Draw a line from a test point to a point that is distant from the curve. Count the number of times the curve crosses the test line from left to right and count the number of times the curve crosses the test line from right to left. If those two numbers are the same the test point is outside the curve otherwise the test point is inside the curve
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed/
---
## EmfPlusFillClosedCurve.Compressed property

Gets or sets a value indicating whether this [`EmfPlusFillClosedCurve`](../) is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. ---------------------- A "winding" fill operation fills areas according to the "even-odd parity" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from the test point to a point that is distant from the curve. If that line crosses the curve an odd number of times, the test point is inside the curve; otherwise, the test point is outside the curve. --------------------- An "alternate" fill operation fills areas according to the "non-zero" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from a test point to a point that is distant from the curve. Count the number of times the curve crosses the test line from left to right, and count the number of times the curve crosses the test line from right to left. If those two numbers are the same, the test point is outside the curve; otherwise, the test point is inside the curve.

```csharp
public bool Compressed { get; set; }
```

### Property Value

`true` if compressed; otherwise, `false`.

### See Also

* class [EmfPlusFillClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusfillclosedcurve/)
* assembly [Aspose.Imaging](../../../)


