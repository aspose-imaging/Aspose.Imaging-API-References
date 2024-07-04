---
title: PathResource Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---

**Summary:** Represents Photoshop Path Resource.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResource

**Aspose.Imaging Version:** 24.7.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathResource()](#PathResource__1) | Initializes a new instance of the PathResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| block_id | short | r/w | Gets or sets the block identifier. |
| name | string | r/w | Gets or sets the name. |
| records | list[aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord] | r/w | Gets or sets the records. |


### Constructor: PathResource() {#PathResource__1}


```
 PathResource() 
```

Initializes a new instance of the PathResource class

## **Examples**
### Transfer Clipping Paths during export from TIFF to PSD image. {#example_104}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PsdOptions

with Image.load("Sample.tif") as image:
	image.save("SampleWithPaths.psd", PsdOptions())

```

