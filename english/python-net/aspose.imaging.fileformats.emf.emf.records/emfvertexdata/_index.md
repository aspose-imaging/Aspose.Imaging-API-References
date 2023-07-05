---
title: EmfVertexData Class
type: docs
weight: 1430
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfVertexData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfVertexData()|Initializes a new instance of the EmfVertexData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|vertex_objects|Gets or sets an array of nVer TriVertex objects (section 2.2.26). Each <br/>            object specifies the position and color of a vertex of either a rectangle or a triangle, <br/>            depending on the value of the ulMode field.|
|vertex_indexes|Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or <br/>            GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. <br/>            Each object specifies indexes into the array of TriVertex objects in the VertexObjects field.|
|vertex_padding|Gets or sets an optional variable-length array of nTri times four bytes <br/>            that MUST be present if the value of the ulMode field indicates GradientRectangle <br/>            objects (section 2.2.7). If the value of the ulMode field indicates GradientTriangle <br/>            objects (section 2.2.8), no VertexPadding is present. This field MUST be ignored.|
