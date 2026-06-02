---
title: "Classe EmfVertexData"
type: docs
weight: 1460
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | Initialise une nouvelle instance de la classe EmfVertexData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | Obtient ou définit un tableau d'objets nTri GradientRectangle (section 2.2.7) ou <br/>            d'objets GradientTriangle (section 2.2.8), selon la valeur du champ ulMode. <br/>            Chaque objet spécifie des index dans le tableau d'objets TriVertex du champ VertexObjects. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | Obtient ou définit un tableau d'objets nVer TriVertex (section 2.2.26). Chaque <br/>            objet spécifie la position et la couleur d'un sommet d'un rectangle ou d'un triangle, <br/>            selon la valeur du champ ulMode. |
| vertex_padding | System.Byte | r/w | Obtient ou définit un tableau optionnel de longueur variable de nTri fois quatre octets <br/>            qui DOIT être présent si la valeur du champ ulMode indique des objets GradientRectangle <br/>            (section 2.2.7). Si la valeur du champ ulMode indique des objets GradientTriangle <br/>            (section 2.2.8), aucun VertexPadding n'est présent. Ce champ DOIT être ignoré. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

Initialise une nouvelle instance de la classe EmfVertexData

