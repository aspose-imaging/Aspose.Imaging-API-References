---
title: EmfEpsData Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

The EpsData object is a container for EPS data

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfEpsData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfEpsData()|Initializes a new instance of the EmfEpsData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|size_data|Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes|
|version|Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. This <br/>            value MUST be 0x00000001|
|points|Gets or sets an array of three Point28_4 objects (section 2.2.23) that defines the <br/>            coordinates of the output parallelogram using 28.4 bit FIX notation|
|post_script_data|Gets or sets an array of bytes of PostScript data. The length of this array can <br/>            be computed from the SizeData field. This data MAY be used to render an image.|
