---
title: "EmfPlusRegionNode Classe"
type: docs
weight: 600
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Inizializza una nuova istanza della classe EmfPlusRegionNode |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Ottiene o imposta dati opzionali a lunghezza variabile che definiscono l'oggetto dati del nodo di regione<br/>            specificato nel campo Type. Il contenuto e<br/>            il formato dei dati possono variare per ogni tipo di nodo di regione.<br/>            Questo campo NON DEVE essere presente se il tipo di nodo è RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite.<br/>            Questo oggetto è generico e viene usato per specificare diversi tipi di dati del nodo di regione, inclusi:<br/>            Un oggetto EmfPlusRegionNodePath (sezione 2.2.2.42), per un nodo terminale;<br/>            Un oggetto EmfPlusRectF (sezione 2.2.2.39), per un nodo terminale; e<br/>            Un oggetto EmfPlusRegionNodeChildNodes (sezione 2.2.2.41), per un nodo non terminale. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di<br/>            dati nel campo RegionNodeData. Questo valore DEVE essere definito nell'enumerazione<br/>            RegionNodeDataType (sezione 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Inizializza una nuova istanza della classe EmfPlusRegionNode

