---
title: "Classe EmfPlusRegionNode"
type: docs
weight: 600
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Initialise une nouvelle instance de la classe EmfPlusRegionNode |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Obtient ou définit des données optionnelles de longueur variable qui définissent l'objet de données du nœud de région<br/>            spécifié dans le champ Type. Le contenu et<br/>            le format des données peuvent différer pour chaque type de nœud de région.<br/>            Ce champ NE DOIT PAS être présent si le type de nœud est RegionNodeDataTypeEmpty ou RegionNodeDataTypeInfinite.<br/>            Cet objet est générique et sert à spécifier différents types de données de nœud de région, notamment :<br/>            Un objet EmfPlusRegionNodePath (section 2.2.2.42), pour un nœud terminal ;<br/>            Un objet EmfPlusRectF (section 2.2.2.39), pour un nœud terminal ; et<br/>            Un objet EmfPlusRegionNodeChildNodes (section 2.2.2.41), pour un nœud non terminal. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de<br/>            données dans le champ RegionNodeData. Cette valeur DOIT être définie dans l'énumération<br/>            RegionNodeDataType (section 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Initialise une nouvelle instance de la classe EmfPlusRegionNode

