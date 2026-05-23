---
title: "EmfVertexData Classe"
type: docs
weight: 1460
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Inizializza una nuova istanza della classe EmfVertexData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Ottiene o imposta un array di oggetti nTri GradientRectangle (sezione 2.2.7) o <br/>            oggetti GradientTriangle (sezione 2.2.8), a seconda del valore del campo ulMode. <br/>            Ogni oggetto specifica gli indici nell'array di oggetti TriVertex nel campo VertexObjects. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Ottiene o imposta un array di oggetti nVer TriVertex (sezione 2.2.26). Ogni <br/>            oggetto specifica la posizione e il colore di un vertice di un rettangolo o di un triangolo, <br/>            a seconda del valore del campo ulMode. |
| vertex_padding | System.Byte | r/w | Ottiene o imposta un array opzionale a lunghezza variabile di nTri per quattro byte <br/>            che MUST essere presente se il valore del campo ulMode indica oggetti GradientRectangle <br/>            (sezione 2.2.7). Se il valore del campo ulMode indica oggetti GradientTriangle <br/>            (sezione 2.2.8), non è presente VertexPadding. Questo campo MUST essere ignorato. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Inizializza una nuova istanza della classe EmfVertexData

