---
title: Class EmfVertexData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfVertexData class. Objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them
type: docs
weight: 4770
url: /net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

Objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them.

```csharp
public sealed class EmfVertexData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfVertexData](emfvertexdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes/) { get; set; } | Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. Each object specifies indexes into the array of TriVertex objects in the VertexObjects field. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects/) { get; set; } | Gets or sets an array of nVer TriVertex objects (section 2.2.26). Each object specifies the position and color of a vertex of either a rectangle or a triangle, depending on the value of the ulMode field. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding/) { get; set; } | Gets or sets an optional variable-length array of nTri times four bytes that MUST be present if the value of the ulMode field indicates GradientRectangle objects (section 2.2.7). If the value of the ulMode field indicates GradientTriangle objects (section 2.2.8), no VertexPadding is present. This field MUST be ignored. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


