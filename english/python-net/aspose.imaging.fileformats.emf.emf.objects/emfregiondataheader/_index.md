---
title: EmfRegionDataHeader Class
type: docs
weight: 250
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

The RegionDataHeader object describes the properties of a RegionData object.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfRegionDataHeader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfRegionDataHeader()|Initializes a new instance of the EmfRegionDataHeader class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|size|Gets or sets a 32-bit unsigned integer that specifies the size of this object in bytes. This MUST be 0x00000020.|
|type|Gets or sets a 32-bit unsigned integer that specifies the region type. This SHOULD be <br/>            RDH_RECTANGLES (0x00000001).|
|count_rects|Gets or sets a 32-bit unsigned integer that specifies the number of rectangles in this region.|
|rgn_size|Gets or sets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes.|
|bounds|Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies <br/>            the bounds of the region.|
