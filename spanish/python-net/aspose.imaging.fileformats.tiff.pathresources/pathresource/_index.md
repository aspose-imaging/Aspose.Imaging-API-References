---
title: "Clase PathResource"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---

**Summary:** Represents Photoshop Path Resource.

**Module:** [aspose.imaging.fileformats.tiff.pathresources](/imaging/python-net/aspose.imaging.fileformats.tiff.pathresources/)

**Full Name:** aspose.imaging.fileformats.tiff.pathresources.PathResource

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PathResource()](#PathResource__1) | Inicializa una nueva instancia de la clase PathResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| block_id | int | r/w | Obtiene o establece el identificador del bloque. |
| nombre | string | r/w | Obtiene o establece el nombre. |
| registros | System.Collections.Generic.List`1[[Aspose.Imaging.FileFormats.Core.VectorPaths.VectorPathRecord]] | r/w | Obtiene o establece los registros. |


### Constructor: PathResource() {#PathResource__1}


```
 PathResource() 
```

Inicializa una nueva instancia de la clase PathResource

## **Examples**
### The following example shows how to create Clipping Path in TIFF image. In order to do that you need to create an instance of PathResource class. The following code demonstrates the way how you can create an empty path in TIFF image. {#example_203}
``` python

import aspose.pycore as aspycore
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage, TiffFrame
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.fileformats.tiff.pathresources import PathResource

options = TiffOptions(TiffExpectedFormat.DEFAULT)
frame = TiffFrame(options, 800, 600)
with TiffImage(frame) as image:
	obj_init = PathResource()
	obj_init.block_id = 2000
	obj_init.name = "My Clipping Path"
	obj_init.records = []
	image.active_frame.path_resources = [obj_init]
	image.save("ImageWithEmptyPath.tiff")


```

### Transfer Clipping Paths during export from TIFF to PSD image. {#example_204}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PsdOptions

with Image.load("Sample.tif") as image:
	image.save("SampleWithPaths.psd", PsdOptions())

```

### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Crea el GraphicsPath usando PathResources de una imagen TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Dibujar una línea roja y guardar la imagen
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

