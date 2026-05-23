---
title: "Класс EmfPlusRegionNode"
type: docs
weight: 600
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Инициализирует новый экземпляр класса EmfPlusRegionNode |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Получает или задает необязательные данные переменной длины, определяющие объект данных узла региона, указанный в поле Type. Содержание и<br/>            формат данных могут различаться для каждого типа узла региона. Это поле НЕ ДОЛЖНО присутствовать, если тип узла<br/>            равен RegionNodeDataTypeEmpty или RegionNodeDataTypeInfinite.<br/>            Этот объект является универсальным и используется для указания различных типов данных узла региона, включая:<br/>            Объект EmfPlusRegionNodePath (section 2.2.2.42) для терминального узла;<br/>            Объект EmfPlusRectF (section 2.2.2.39) для терминального узла; и<br/>            Объект EmfPlusRegionNodeChildNodes (section 2.2.2.41) для нетерминального узла. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Получает или задает 32‑битное беззнаковое целое, определяющее тип<br/>            данных в поле RegionNodeData. Это значение ДОЛЖНО быть определено в перечислении RegionNodeDataType (section 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Инициализирует новый экземпляр класса EmfPlusRegionNode

