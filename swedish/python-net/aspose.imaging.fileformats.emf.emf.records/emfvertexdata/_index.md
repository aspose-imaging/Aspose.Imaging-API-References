---
title: "EmfVertexData klass"
type: docs
weight: 1460
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Initierar en ny instans av EmfVertexData klass |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Hämtar eller anger en array av nTri GradientRectangle‑objekt (avsnitt 2.2.7) eller <br/>            GradientTriangle‑objekt (avsnitt 2.2.8), beroende på värdet i ulMode‑fältet. <br/>            Varje objekt specificerar index i arrayen av TriVertex‑objekt i VertexObjects‑fältet. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Hämtar eller anger en array av nVer TriVertex‑objekt (avsnitt 2.2.26). Varje <br/>            objekt specificerar position och färg för en vertex av antingen en rektangel eller en triangel, <br/>            beroende på värdet i ulMode‑fältet. |
| vertex_padding | System.Byte | r/w | Hämtar eller anger en valfri variabel‑längd array av nTri gånger fyra byte <br/>            som MÅSTE finnas om värdet i ulMode‑fältet indikerar GradientRectangle‑objekt <br/>            (avsnitt 2.2.7). Om värdet i ulMode‑fältet indikerar GradientTriangle‑objekt <br/>            (avsnitt 2.2.8), finns ingen VertexPadding. Detta fält MÅSTE ignoreras. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Initierar en ny instans av EmfVertexData klass

