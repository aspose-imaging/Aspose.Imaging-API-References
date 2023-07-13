---
title: EmfPlusRegion Class
type: docs
weight: 590
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---

The EmfPlusRegion object specifies line and curve segments that define a non rectilinear shape

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegion

**Inheritance:** EmfPlusGraphicsObjectType

**Aspose.Imaging Version:** 23.6

The EmfPlusRegion type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusRegion()](#EmfPlusRegion__0) | Initializes a new instance of the EmfPlusRegion class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) | r/w | Gets or sets the version. |
| region_node | [EmfPlusRegionNode[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) | r/w | Gets or sets an array of RegionNodeCount+1 EmfPlusRegionNode objects <br/>            (section 2.2.2.40). Regions are specified as a binary tree <br/>            of region nodes, and each node MUST either be a terminal <br/>            node or specify one or two child nodes. <br/>            RegionNode MUST contain at least one element |

### EmfPlusRegion() {#EmfPlusRegion__0}


```
 EmfPlusRegion() 
```

Initializes a new instance of the EmfPlusRegion class

