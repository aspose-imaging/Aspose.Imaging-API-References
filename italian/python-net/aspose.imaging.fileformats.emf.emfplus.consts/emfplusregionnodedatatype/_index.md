---
title: "EmfPlusRegionNodeDataType Enumeration"
type: docs
weight: 370
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

L'enumerazione RegionNodeDataType definisce i tipi di dati dei nodi di regione.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | Specifica un nodo di regione con nodi figlio. Un'operazione Boolean AND DOVREBBE essere applicata ai nodi figlio sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) (sezione 2.2.2.41). |
| REGION_NODE_DATA_TYPE_COMPLEMENT | Specifica un nodo di regione con nodi figlio. Un'operazione Boolean, definita come "la parte della regione 2 che è esclusa dalla regione 1", DOVREBBE essere applicata ai nodi figlio sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_EMPTY | Specifica un nodo di regione senza nodi figlio. Il campo RegionNodeData NON DOVREBBE essere presente |
| REGION_NODE_DATA_TYPE_EXCLUDE | Specifica un nodo di regione con nodi figlio. Un'operazione Boolean, definita come "la parte della regione 1 che è esclusa dalla regione 2", DOVREBBE essere applicata ai nodi figlio sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_INFINITE | Specifica un nodo di regione senza nodi figlio, e i suoi limiti non sono definiti. |
| REGION_NODE_DATA_TYPE_OR | Specifica un nodo di regione con nodi figlio. Un'operazione Boolean OR DOVREBBE essere applicata ai nodi figlio sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_PATH | Specifica un nodo di regione senza nodi figlio. Il campo RegionNodeData DOVREBBE specificare un confine con un oggetto [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) (sezione 2.2.2.42). |
| REGION_NODE_DATA_TYPE_RECT | Specifica un nodo di regione senza nodi figlio. Il campo RegionNodeData DOVREBBE specificare un confine con un oggetto [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) (sezione 2.2.2.39). |
| REGION_NODE_DATA_TYPE_XOR | Specifica un nodo di regione con nodi figlio. Un'operazione Boolean XOR DOVREBBE essere applicata ai nodi figlio sinistro e destro specificati da un oggetto [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
