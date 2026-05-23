---
title: "Clase EmfVertexData"
type: docs
weight: 1460
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Inicializa una nueva instancia de la clase EmfVertexData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Obtiene o establece una matriz de nTri objetos GradientRectangle (sección 2.2.7) o <br/>            objetos GradientTriangle (sección 2.2.8), dependiendo del valor del campo ulMode. <br/>            Cada objeto especifica índices en la matriz de objetos TriVertex del campo VertexObjects. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Obtiene o establece una matriz de nVer objetos TriVertex (sección 2.2.26). Cada <br/>            objeto especifica la posición y el color de un vértice de un rectángulo o un triángulo, <br/>            dependiendo del valor del campo ulMode. |
| vertex_padding | System.Byte | r/w | Obtiene o establece una matriz opcional de longitud variable de nTri por cuatro bytes <br/>            que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle <br/>            (sección 2.2.7). Si el valor del campo ulMode indica objetos GradientTriangle <br/>            (sección 2.2.8), no hay VertexPadding presente. Este campo DEBE ser ignorado. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Inicializa una nueva instancia de la clase EmfVertexData

