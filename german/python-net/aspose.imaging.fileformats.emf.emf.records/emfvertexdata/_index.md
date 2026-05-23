---
title: "EmfVertexData Klasse"
type: docs
weight: 1460
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Initialisiert eine neue Instanz der EmfVertexData Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Ruft ein Array von nTri GradientRectangle‑Objekten (Abschnitt 2.2.7) oder <br/>            GradientTriangle‑Objekten (Abschnitt 2.2.8) ab bzw. legt es fest, abhängig vom Wert des ulMode‑Feldes. <br/>            Jedes Objekt gibt Indizes in das Array von TriVertex‑Objekten im Feld VertexObjects an. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Ruft ein Array von nVer TriVertex‑Objekten (Abschnitt 2.2.26) ab bzw. legt es fest. Jedes <br/>            Objekt gibt die Position und Farbe eines Scheitelpunkts eines Rechtecks oder eines Dreiecks an, <br/>            abhängig vom Wert des ulMode‑Feldes. |
| vertex_padding | System.Byte | r/w | Ruft ein optionales variabel langes Array von nTri mal vier Bytes <br/>            ab bzw. legt es fest, das MUSS vorhanden sein, wenn der Wert des ulMode‑Feldes GradientRectangle‑Objekte <br/>            (Abschnitt 2.2.7) anzeigt. Wenn der Wert des ulMode‑Feldes GradientTriangle‑Objekte <br/>            (Abschnitt 2.2.8) anzeigt, ist kein VertexPadding vorhanden. Dieses Feld MUSS ignoriert werden. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Initialisiert eine neue Instanz der EmfVertexData Klasse

