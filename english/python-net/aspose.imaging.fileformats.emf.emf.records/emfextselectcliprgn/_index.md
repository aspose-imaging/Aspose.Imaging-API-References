---
title: EmfExtSelectClipRgn Class
type: docs
weight: 450
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---

The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region <br/>            using the specified mode. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtSelectClipRgn

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfExtSelectClipRgn type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfExtSelectClipRgn(source)|Initializes a new instance of the EmfExtSelectClipRgn class|
|EmfExtSelectClipRgn()|Initializes a new instance of the [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|rgn_data_size|Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes.|
|region_mode|Gets or sets a 32-bit unsigned integer that specifies the way to use the region. The <br/>            value MUST be in the RegionMode (section 2.1.29) enumeration.|
|rgn_data|Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object <br/>            in logical units. If RegionMode is RGN_COPY, this data can be omitted and the clip region <br/>            SHOULD be set to the default (NULL) clip region.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
