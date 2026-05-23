---
title: "EmfPlusRegionNodeDataType Aufzählung"
type: docs
weight: 370
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

Die RegionNodeDataType-Aufzählung definiert Arten von Regionsknoten-Daten.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche UND-Operation SOLL auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) Objekt (Abschnitt 2.2.2.41) angegeben sind. |
| REGION_NODE_DATA_TYPE_COMPLEMENT | Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche Operation, definiert als "der Teil von Region 2, der von Region 1 ausgeschlossen ist", SOLL auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) Objekt angegeben sind. |
| REGION_NODE_DATA_TYPE_EMPTY | Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLL NICHT vorhanden sein. |
| REGION_NODE_DATA_TYPE_EXCLUDE | Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche Operation, definiert als "der Teil von Region 1, der von Region 2 ausgeschlossen ist", SOLL auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) Objekt angegeben sind. |
| REGION_NODE_DATA_TYPE_INFINITE | Gibt einen Regionsknoten ohne Kindknoten an, und seine Grenzen sind nicht definiert. |
| REGION_NODE_DATA_TYPE_OR | Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche ODER-Operation SOLL auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) Objekt angegeben sind. |
| REGION_NODE_DATA_TYPE_PATH | Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLL eine Grenze mit einem [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) Objekt (Abschnitt 2.2.2.42) angeben. |
| REGION_NODE_DATA_TYPE_RECT | Gibt einen Regionsknoten ohne Kindknoten an. Das Feld RegionNodeData SOLL eine Grenze mit einem [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) Objekt (Abschnitt 2.2.2.39) angeben. |
| REGION_NODE_DATA_TYPE_XOR | Gibt einen Regionsknoten mit Kindknoten an. Eine boolesche XOR-Operation SOLL auf die linken und rechten Kindknoten angewendet werden, die durch ein [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) Objekt angegeben sind. |
