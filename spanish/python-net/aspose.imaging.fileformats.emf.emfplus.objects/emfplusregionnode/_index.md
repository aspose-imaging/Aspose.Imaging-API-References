---
title: "Clase EmfPlusRegionNode"
type: docs
weight: 600
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Inicializa una nueva instancia de la clase EmfPlusRegionNode |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Obtiene o establece datos opcionales de longitud variable que definen el objeto de datos del nodo de región<br/>            especificado en el campo Type. El contenido y<br/>            formato de los datos pueden ser diferentes para cada tipo de nodo<br/>            de región. Este campo NO DEBE estar presente si el nodo<br/>            es de tipo RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite.<br/>            Este objeto es genérico y se utiliza para especificar diferentes tipos de datos de nodo de región, incluyendo:<br/>            Un objeto EmfPlusRegionNodePath (sección 2.2.2.42), para un nodo terminal;<br/>            Un objeto EmfPlusRectF (sección 2.2.2.39), para un nodo terminal; y<br/>            Un objeto EmfPlusRegionNodeChildNodes (sección 2.2.2.41), para un nodo no terminal. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de<br/>            datos en el campo RegionNodeData. Este valor DEBE estar definido en la<br/>            enumeración RegionNodeDataType (sección 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Inicializa una nueva instancia de la clase EmfPlusRegionNode

