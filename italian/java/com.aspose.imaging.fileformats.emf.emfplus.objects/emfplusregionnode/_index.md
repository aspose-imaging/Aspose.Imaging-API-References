---
title: "EmfPlusRegionNode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusRegionNode specifica i nodi di una regione grafica."
type: docs
weight: 69
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusRegionNode specifica i nodi di una regione grafica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Ottiene o imposta un dato opzionale a lunghezza variabile che definisce l'oggetto dati del nodo di regione specificato nel campo Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Ottiene o imposta un dato opzionale a lunghezza variabile che definisce l'oggetto dati del nodo di regione specificato nel campo Type. |
| [getType()](#getType--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di dati nel campo RegionNodeData. |
| [setType(int value)](#setType-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di dati nel campo RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Ottiene o imposta un dato opzionale a lunghezza variabile che definisce l'oggetto dati del nodo di regione specificato nel campo Type. Il contenuto e il formato dei dati possono essere diversi per ogni tipo di nodo di regione. Questo campo NON DEVE essere presente se il tipo di nodo è RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite. Questo oggetto è generico e viene usato per specificare diversi tipi di dati del nodo di regione, includendo: un oggetto EmfPlusRegionNodePath (sezione 2.2.2.42), per un nodo terminale; un oggetto EmfPlusRectF (sezione 2.2.2.39), per un nodo terminale; e un oggetto EmfPlusRegionNodeChildNodes (sezione 2.2.2.41), per un nodo non terminale.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Ottiene o imposta un dato opzionale a lunghezza variabile che definisce l'oggetto dati del nodo di regione specificato nel campo Type. Il contenuto e il formato dei dati possono essere diversi per ogni tipo di nodo di regione. Questo campo NON DEVE essere presente se il tipo di nodo è RegionNodeDataTypeEmpty o RegionNodeDataTypeInfinite. Questo oggetto è generico e viene usato per specificare diversi tipi di dati del nodo di regione, includendo: un oggetto EmfPlusRegionNodePath (sezione 2.2.2.42), per un nodo terminale; un oggetto EmfPlusRectF (sezione 2.2.2.39), per un nodo terminale; e un oggetto EmfPlusRegionNodeChildNodes (sezione 2.2.2.41), per un nodo non terminale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di dati nel campo RegionNodeData. Questo valore DEVE essere definito nell'enumerazione RegionNodeDataType (sezione 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di dati nel campo RegionNodeData. Questo valore DEVE essere definito nell'enumerazione RegionNodeDataType (sezione 2.1.1.27).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

