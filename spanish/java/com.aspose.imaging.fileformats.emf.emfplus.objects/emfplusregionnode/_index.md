---
title: "EmfPlusRegionNode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusRegionNode especifica nodos de una región gráfica."
type: docs
weight: 69
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

El objeto EmfPlusRegionNode especifica nodos de una región gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Obtiene o establece un dato opcional de longitud variable que define el objeto de datos del nodo de región especificado en el campo Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Obtiene o establece un dato opcional de longitud variable que define el objeto de datos del nodo de región especificado en el campo Type. |
| [getType()](#getType--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de datos en el campo RegionNodeData. |
| [setType(int value)](#setType-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de datos en el campo RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Obtiene o establece un dato opcional de longitud variable que define el objeto de datos del nodo de región especificado en el campo Type. El contenido y formato de los datos pueden ser diferentes para cada tipo de nodo de región. Este campo NO DEBE estar presente si el tipo de nodo es RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite. Este objeto es genérico y se utiliza para especificar diferentes tipos de datos de nodo de región, incluyendo: un objeto EmfPlusRegionNodePath (sección 2.2.2.42), para un nodo terminal; un objeto EmfPlusRectF (sección 2.2.2.39), para un nodo terminal; y un objeto EmfPlusRegionNodeChildNodes (sección 2.2.2.41), para un nodo no terminal.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Obtiene o establece un dato opcional de longitud variable que define el objeto de datos del nodo de región especificado en el campo Type. El contenido y formato de los datos pueden ser diferentes para cada tipo de nodo de región. Este campo NO DEBE estar presente si el tipo de nodo es RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite. Este objeto es genérico y se utiliza para especificar diferentes tipos de datos de nodo de región, incluyendo: un objeto EmfPlusRegionNodePath (sección 2.2.2.42), para un nodo terminal; un objeto EmfPlusRectF (sección 2.2.2.39), para un nodo terminal; y un objeto EmfPlusRegionNodeChildNodes (sección 2.2.2.41), para un nodo no terminal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de datos en el campo RegionNodeData. Este valor DEBE estar definido en la enumeración RegionNodeDataType (sección 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de datos en el campo RegionNodeData. Este valor DEBE estar definido en la enumeración RegionNodeDataType (sección 2.1.1.27).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

