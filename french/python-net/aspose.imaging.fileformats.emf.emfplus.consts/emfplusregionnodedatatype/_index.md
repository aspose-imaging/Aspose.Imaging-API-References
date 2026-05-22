---
title: "EmfPlusRegionNodeDataType Énumération"
type: docs
weight: 370
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

L'énumération RegionNodeDataType définit les types de données de nœuds de région.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne AND DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) (section 2.2.2.41). |
| REGION_NODE_DATA_TYPE_COMPLEMENT | Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne, définie comme « la partie de la région 2 qui est exclue de la région 1 », DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_EMPTY | Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData NE DOIT PAS être présent |
| REGION_NODE_DATA_TYPE_EXCLUDE | Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne, définie comme « la partie de la région 1 qui est exclue de la région 2 », DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_INFINITE | Spécifie un nœud de région sans nœuds enfants, et ses limites ne sont pas définies. |
| REGION_NODE_DATA_TYPE_OR | Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne OR DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
| REGION_NODE_DATA_TYPE_PATH | Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData DOIT spécifier une frontière avec un objet [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) (section 2.2.2.42). |
| REGION_NODE_DATA_TYPE_RECT | Spécifie un nœud de région sans nœuds enfants. Le champ RegionNodeData DOIT spécifier une frontière avec un objet [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) (section 2.2.2.39). |
| REGION_NODE_DATA_TYPE_XOR | Spécifie un nœud de région avec des nœuds enfants. Une opération booléenne XOR DOIT être appliquée aux nœuds enfants gauche et droit spécifiés par un objet [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/). |
