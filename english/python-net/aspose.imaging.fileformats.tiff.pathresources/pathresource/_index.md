---
title: PathResource Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---

**Summary:** Represents Photoshop Path Resource.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResource

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
### Transfer Clipping Paths during export from TIFF to PSD image. {#example_149}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PsdOptions

with Image.load("Sample.tif") as image:
	image.save("SampleWithPaths.psd", PsdOptions())

```

### Create Graphics Path from Path Resources in TIFF image. {#example_154}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Create the GraphicsPath using PathResources from TIFF image
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Draw red line and save the image
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

