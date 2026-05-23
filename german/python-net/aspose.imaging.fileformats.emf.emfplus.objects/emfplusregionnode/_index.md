---
title: "EmfPlusRegionNode Klasse"
type: docs
weight: 600
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Initialisiert eine neue Instanz der EmfPlusRegionNode Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Liest oder schreibt optionale, variable Daten, die das Region‑Node‑Datenobjekt definieren, das im Feld Type angegeben ist. Der Inhalt und das Format der Daten können für jeden Region‑Node‑Typ unterschiedlich sein. Dieses Feld DARF NICHT vorhanden sein, wenn der Node‑Typ RegionNodeDataTypeEmpty oder RegionNodeDataTypeInfinite ist. Dieses Objekt ist generisch und wird verwendet, um verschiedene Arten von Region‑Node‑Daten anzugeben, einschließlich:<br/>            Ein EmfPlusRegionNodePath‑Objekt (Abschnitt 2.2.2.42) für einen Terminal‑Node;<br/>            Ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39) für einen Terminal‑Node; und<br/>            Ein EmfPlusRegionNodeChildNodes‑Objekt (Abschnitt 2.2.2.41) für einen Nicht‑Terminal‑Node. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Liest oder schreibt eine 32‑Bit vorzeichenlose Ganzzahl, die den Typ der Daten im Feld RegionNodeData angibt. Dieser Wert MUSS in der Aufzählung RegionNodeDataType (Abschnitt 2.1.1.27) definiert sein. |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Initialisiert eine neue Instanz der EmfPlusRegionNode Klasse

