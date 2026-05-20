---
title: "EmfPlusRegionNode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusRegionNode spécifie les nœuds d'une région graphique."
type: docs
weight: 69
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

L'objet EmfPlusRegionNode spécifie les nœuds d'une région graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Obtient ou définit des données optionnelles de longueur variable qui définissent l'objet de données du nœud de région spécifié dans le champ Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Obtient ou définit des données optionnelles de longueur variable qui définissent l'objet de données du nœud de région spécifié dans le champ Type. |
| [getType()](#getType--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de données dans le champ RegionNodeData. |
| [setType(int value)](#setType-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de données dans le champ RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Obtient ou définit des données optionnelles de longueur variable qui définissent l'objet de données du nœud de région spécifié dans le champ Type. Le contenu et le format des données peuvent différer pour chaque type de nœud de région. Ce champ NE DOIT PAS être présent si le type de nœud est RegionNodeDataTypeEmpty ou RegionNodeDataTypeInfinite. Cet objet est générique et est utilisé pour spécifier différents types de données de nœud de région, y compris : un objet EmfPlusRegionNodePath (section 2.2.2.42), pour un nœud terminal ; un objet EmfPlusRectF (section 2.2.2.39), pour un nœud terminal ; et un objet EmfPlusRegionNodeChildNodes (section 2.2.2.41), pour un nœud non terminal.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Obtient ou définit des données optionnelles de longueur variable qui définissent l'objet de données du nœud de région spécifié dans le champ Type. Le contenu et le format des données peuvent différer pour chaque type de nœud de région. Ce champ NE DOIT PAS être présent si le type de nœud est RegionNodeDataTypeEmpty ou RegionNodeDataTypeInfinite. Cet objet est générique et est utilisé pour spécifier différents types de données de nœud de région, y compris : un objet EmfPlusRegionNodePath (section 2.2.2.42), pour un nœud terminal ; un objet EmfPlusRectF (section 2.2.2.39), pour un nœud terminal ; et un objet EmfPlusRegionNodeChildNodes (section 2.2.2.41), pour un nœud non terminal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le type de données dans le champ RegionNodeData. Cette valeur DOIT être définie dans l'énumération RegionNodeDataType (section 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le type de données dans le champ RegionNodeData. Cette valeur DOIT être définie dans l'énumération RegionNodeDataType (section 2.1.1.27).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

