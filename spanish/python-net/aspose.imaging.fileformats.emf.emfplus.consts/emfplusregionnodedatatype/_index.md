---
title: "EmfPlusRegionNodeDataType Enumeration"
type: docs
weight: 370
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

La enumeración RegionNodeDataType define tipos de datos de nodos de región.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación BOOLEANA AND a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) (sección 2.2.2.41). |
| REGION_NODE_DATA_TYPE_COMPLEMENT | Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación BOOLEANA, definida como "la parte de la región 2 que se excluye de la región 1", a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_EMPTY | Especifica un nodo de región sin nodos hijos. El campo RegionNodeData NO DEBE estar presente |
| REGION_NODE_DATA_TYPE_EXCLUDE | Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación BOOLEANA, definida como "la parte de la región 1 que se excluye de la región 2", a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_INFINITE | Especifica un nodo de región sin nodos hijos, y sus límites no están definidos. |
| REGION_NODE_DATA_TYPE_OR | Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación BOOLEANA OR a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_PATH | Especifica un nodo de región sin nodos hijos. El campo RegionNodeData DEBE especificar un límite con un objeto [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) (sección 2.2.2.42). |
| REGION_NODE_DATA_TYPE_RECT | Especifica un nodo de región sin nodos hijos. El campo RegionNodeData DEBE especificar un límite con un objeto [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) (sección 2.2.2.39). |
| REGION_NODE_DATA_TYPE_XOR | Especifica un nodo de región con nodos hijos. Se DEBE aplicar una operación BOOLEANA XOR a los nodos hijos izquierdo y derecho especificados por un objeto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
