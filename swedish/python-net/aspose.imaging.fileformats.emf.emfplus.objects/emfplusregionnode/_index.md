---
title: "EmfPlusRegionNode-klass"
type: docs
weight: 600
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Initierar en ny instans av EmfPlusRegionNode-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Hämtar eller anger valfri, variabel längd data som definierar regionnodens<br/>            dataobjekt som anges i Type‑fältet. Innehållet och<br/>            formatet på datan kan vara olika för varje regionnod‑typ. Detta fält FÅR INTE vara närvarande om nod‑typen är RegionNodeDataTypeEmpty eller RegionNodeDataTypeInfinite.<br/>            Detta objekt är generiskt och används för att specificera olika typer av regionnod‑data, inklusive:<br/>            Ett EmfPlusRegionNodePath‑objekt (avsnitt 2.2.2.42), för en terminalnod;<br/>            Ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39), för en terminalnod; och<br/>            Ett EmfPlusRegionNodeChildNodes‑objekt (avsnitt 2.2.2.41), för en icke‑terminalnod. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar typen av<br/>            data i RegionNodeData‑fältet. Detta värde MÅSTE vara definierat i<br/>            RegionNodeDataType‑enumerationen (avsnitt 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Initierar en ny instans av EmfPlusRegionNode-klassen

